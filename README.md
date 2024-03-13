# trithiam.github.io
# Resume for Willy Trethewey

# Personal Information
name = "Willy Trethewey"
age = 23

# Education
education = {
    "University": Payap {
        "Name": university,
        "Degree": "Bachelor's Degree",
        "Major": English Comunnication,
        "Expected_Graduation": "2024"
    }
}

# Experience
experience = [
    {
        "Position": "English Tutor",
        "Company": "Private Tutoring",
        "Duration": "September 2021 - Present",
        "Responsibilities": [
            "Providing personalized English language tutoring sessions to students",
            "Creating lesson plans tailored to individual student needs",
            "Assessing student progress and adjusting teaching methods accordingly"
        ]
    },
    {
        "Position": "Social Media Intern",
        "Company": "Digital Marketing Agency",
        "Duration": "June 2021 - August 2021",
        "Responsibilities": [
            "Assisting in the management of social media accounts",
            "Creating engaging content for various platforms",
            "Analyzing social media metrics and trends"
        ]
    }
]

# Skills
skills = ["Excellent verbal and written communication skills",
          "Proficient in Microsoft Office Suite",
          "Strong interpersonal skills",
          "Creative problem solver",
          "Adaptable and quick learner",
          "Basic knowledge of graphic design tools"]

# References
references_available = True

# Print Resume
print("Resume for:", name)
print("Age:", age)
print("University:", university)
print("Major:", major)
print("\nEducation:")
for key, value in education["University"].items():
    print(key + ":", value)
print("\nExperience:")
for exp in experience:
    print("- Position:", exp["Position"])
    print("  Company:", exp["Company"])
    print("  Duration:", exp["Duration"])
    print("  Responsibilities:")
    for resp in exp["Responsibilities"]:
        print("  -", resp)
print("\nSkills:")
for skill in skills:
    print("-", skill)
if references_available:
    print("\nReferences available upon request.")
