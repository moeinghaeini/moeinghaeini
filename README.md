```cpp
#include <iostream>
#include <string>
#include <vector>
#include <aws/core/Aws.h>

class MoeinGhaeini {
private:
    std::string name = "Moein Ghaeini";
    std::string role = "Cloud Data Engineer & Solution Architect";
    std::vector<std::string> expertise = {
        "Data Engineering", "Solution Architecture", "AWS Services"
    };
    
public:
    void displayProfile() {
        std::cout << "\n🚀 " << name << std::endl;
        std::cout << "💼 " << role << std::endl;
        std::cout << "\n📋 Core Expertise:" << std::endl;
        
        for (const auto& skill : expertise) {
            std::cout << "   ⚡ " << skill << std::endl;
        }
    }
    
    void showContact() {
        std::cout << "\n📞 Contact Information:" << std::endl;
        std::cout << "    GitHub:    https://github.com/moeinghaeini" << std::endl;
        std::cout << "   LinkedIn:  https://www.linkedin.com/in/moeinghaeini/" << std::endl;
        std::cout << "   Business Card:   https://www.moeinghaeini.com/" << std::endl;
        std::cout << "   📧 Email:     moeinghaeini@gmail.com" << std::endl;
    }
};

int main() {
    MoeinGhaeini profile;
    profile.displayProfile();
    profile.showContact();
    
    std::cout << "\n✨ Let's build amazing cloud solutions together! ✨" << std::endl;
    return 0;
}
```


---

<div align="center">

**🌟 "Get In Touch" 🌟**

[![Website](https://img.shields.io/badge/Business%20Card-FF5722?style=for-the-badge&logo=firefox&logoColor=white)](https://www.moeinghaeini.com/)

</div>