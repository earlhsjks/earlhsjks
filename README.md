```
#include <iostream>
#include <vector>
using namespace std;

struct Introduction {
    string name = "Earl Jeno Garcia";
    string profession = "IT Student & Aspiring Developer";
    string location = "Philippines";
    vector<string> passions = {"Backend Development", "Continuous Learning"};
    vector<string> skills = {"C++", "Python", "SQL", "Flask", "Django", "HTML", "CSS"};
    string portfolio = "https://yourportfolio.com/";
    string github = "https://github.com/jenogarcia";
    vector<string> socialMedia = {"https://jenogarcia.com/"};
    string quote = "Ad Astra Per Aspera.";
};

void introduceMyself(const Introduction& intro) {
    cout << "Hi there, I'm " << intro.name << ", a " << intro.profession 
         << " from " << intro.location << ".\nMy passion lies in " 
         << intro.passions[0] << " and " << intro.passions[1] 
         << ", and I continuously strive to expand my skillset and knowledge in ";

    for (size_t i = 0; i < intro.skills.size(); i++) {
        cout << intro.skills[i];
        if (i != intro.skills.size() - 1) cout << ", ";
    }

    cout << ".\nI actively contribute to projects on GitHub (" << intro.github 
         << "), and my portfolio (" << intro.portfolio << ") showcases some of my work.\n"
         << "If you're interested in my journey, feel free to connect with me on my socials: ";

    for (size_t i = 0; i < intro.socialMedia.size(); i++) {
        cout << intro.socialMedia[i];
        if (i != intro.socialMedia.size() - 1) cout << ", ";
    }

    cout << ".\n\nOne of my favorite quotes is: \"" << intro.quote << "\".\n"
         << "Let's connect and create something amazing together!\n";
}

int main() {
    Introduction intro;
    introduceMyself(intro);
    return 0;
}
```

### 📊 GitHub Stats  
![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=earlhsjks&show_icons=true&theme=dark) ![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=earlhsjks&layout=compact&theme=dark)

### 🚀 Programming Languages
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" alt="SQL" width="40" height="40"/>
</p>

### 🛠 Tools and Technologies
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/flask/flask-original.svg" alt="Flask" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/django/django-plain.svg" alt="Django" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" alt="Bootstrap" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" alt="VS Code" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" width="40" height="40"/>
</p>
