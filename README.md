impl Yifan {
    pub fn about() -> Self {
        Self {
            name: "Yifan Liu",
            email: "0219lyf@gmail.com",
            education: Education {
                bachelor: Degree("Northwest A&F University", "Software Engineering", 2018..=2022),
                master: Degree("Northwestern Polytechnical University", ""Software Engineering", 2024..=2027),
            },
        }
    }
}

impl Programmer for Yifan {
    fn topics(&self) -> Vec<&'static str> {
        vec!["Storage Systems"]
    }

    fn languages(&self) -> Vec<&'static str> {
        vec!["Rust", "C++"]
    }
}

<!---
yifaaan/yifaaan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
