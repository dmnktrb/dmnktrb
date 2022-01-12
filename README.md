- 👋 Hi, I’m Dominik.
- 👀 I’m interested in ...
- 🌱 I’m currently learning Python, HTML
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
dmnktrb/dmnktrb is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
- uses: Platane/snk@master
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # path of the generated gif file
    # If left empty, the gif file will not be generated
    gif_out_path: dist/github-snake.gif

    # path of the generated svg file
    # If left empty, the svg file will not be generated
    svg_out_path: dist/github-snake.svg
