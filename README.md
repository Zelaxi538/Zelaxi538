- 👋 Hi, I’m @Zelaxi538
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Zelaxi538/Zelaxi538 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

        //saga yada çepe basanymyzda samalyodumuz girdigimiz gradusa göre Öwürmek üçin ulanylyan kod
     if (Input.GetKeyDown(KeyCode.LeftArrow))
    {
        this.transform.eulerAngles = new Vector3(this.transform.eulerAngles.x,
             rdegree,this.transform.eulerAngles.z);
    }

    if (Input.GetKeyUp(KeyCode.LeftArrow)) 
    {
        this.transform.eulerAngles = new Vector3(this.transform.eulerAngles.x,
             0,this.transform.eulerAngles.z);
    }

    if (Input.GetKeyDown(KeyCode.RightArrow))
    {
        this.transform.eulerAngles = new Vector3(this.transform.eulerAngles.x,
             -rdegree, this.transform.eulerAngles.z);
    }
    if (Input.GetKeyUp(KeyCode.RightArrow))
    {
        this.transform.eulerAngles = new Vector3(this.transform.eulerAngles.x,
             -0, this.transform.eulerAngles.z);
    }
