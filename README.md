def generate_readme(sageSamuel):
    readme_content = f"""
# Hi there, I'm {sageSamuel} 👋

![GitHub followers](https://img.shields.io/github/followers/{sageSamuel}?style=social)
![GitHub User's stars](https://img.shields.io/github/stars/{sageSamuel}?style=social)

## About Me

I'm a passionate developer with a love for learning and creating. Here are some of the technologies I work with:

- **Languages**: Python, JavaScript, C++, Java
- **Frameworks**: React, Node.js, Django, Flask
- **Tools**: Git, Docker, Kubernetes, VS Code

## Projects

### Project 1: Awesome Project
A brief description of your project. [GitHub Repository](https://github.com/{sageSamuel}/awesome-project)

### Project 2: Another Awesome Project
A brief description of your project. [GitHub Repository](https://github.com/{sageSamuel}/another-awesome-project)

## GitHub Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?sageSamuel={sageSamuel}&show_icons=true&theme=radical)

## Connect with Me

- [LinkedIn](https://www.linkedin.com/in/{Samuel Brefo})
- [Twitter](https://twitter.com/{Samuel Brefo})
- [Email](mailto:{samuelbrefomarfo1047@gmail.com)

Thanks for visiting my profile!
"""
    with open("README.md", "w") as file:
        file.write(readme_content)

# Replace 'your-username' with your actual GitHub username
generate_readme('your-username')
