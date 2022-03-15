- 👋 Hi, I’m @awilso15
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
awilso15/awilso15 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

 public Ninjas(String name, int chakraPoints, String bloodLineType, String village) {
        this.name = name;
        this.chakraPoints = chakraPoints;
        this.bloodLineType = bloodLineType;
        this.village = village;


    }

    public void bloodlineAttack() {
        if (chakraPoints > 25) {
            System.out.println(name + "uses 25 chakra points to use " +bloodLineType);
            chakraPoints - 25 = chakraPoints;
            if(chakraPoints < 25) {
                System.out.println(name + " doesn't have enough chakra to use " +bloodLineType);
            }

        }
    }
}







