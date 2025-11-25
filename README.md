### 👋 Hi there, I'm Ahmed Q.

// 🚀 Founder of AQ Systems | C++ Developer

#include <iostream>
#include <vector>
#include <string>

class AQ_Systems {
public:
    std::string focus = "System Architecture & Web Solutions";
    std::string location = "Istanbul, Turkey";
    
    void current_status() {
        std::cout << "Building robust systems and scaling digital ideas." << std::endl;
    }
    
    std::vector<std::string> skills() {
        return { "C++ (STL)", "OOP", "System Design", "Web Development", "Problem Solving" };
    }
};

int main() {
    AQ_Systems founder;
    founder.current_status();
    return 0;
}
