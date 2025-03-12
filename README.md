```
#include <iostream>
#include <vector>
using namespace std;

struct Introduction {
    string name = "Earl Jeno Garcia";
    string profession = "IT Student & Aspiring Developer";
    string location = "Philippines";
    vector<string> passions = {"Backend Development", "Continuous Learning"};
    vector<string> skills = {"C++", "Java", Python", "SQL", "Flask", "Django", "HTML", "CSS"};
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

## 📊 GitHub Stats  
![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=earlhsjks&show_icons=true&theme=dark) ![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=earlhsjks&layout=compact&theme=dark)

## 🚀 Programming Languages
<p align="left">
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sqlite&logoColor=white"/>
</p>

## 🛠 Tools and Technologies
<p align="left">
  <img src="https://img.shields.io/badge/-Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"/>
  <img src="https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/-VS_Code-007ACC?style=for-the-badge&logo=visual%20studio%20code&logoColor=white"/>
  <img src="https://img.shields.io/badge/-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
</p>

