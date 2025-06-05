# 🎓 UiPath Certificate Generator

This UiPath automation project is designed to **generate certificates** using a pre-defined Word template. It simplifies the process of creating personalized certificates from structured data (e.g., Excel), making it ideal for events, workshops, trainings, or academic purposes.

---

## 📂 Project Structure

- `Main.xaml` – The main workflow that controls the certificate generation logic.
- `project.json` – Project metadata and dependency definitions.

---

## ⚙️ Dependencies

This project uses the following UiPath packages:

- `UiPath.Excel.Activities` [2.11.4]
- `UiPath.Mail.Activities` [1.12.3]
- `UiPath.System.Activities` [21.10.6]
- `UiPath.UIAutomation.Activities` [21.10.8]
- `UiPath.Word.Activities` [1.18.1]

Make sure all dependencies are restored before running the workflow.

---

## 🛠️ How It Works

1. Reads data from an Excel sheet containing recipient details.
2. Opens a Word certificate template.
3. Replaces placeholders with personalized details (e.g., Name, Course, Date).
4. Saves or prints the filled certificate.

---

## 🧪 Prerequisites

- UiPath Studio (Recommended: v21.10.10 or higher)
- Microsoft Word installed (for Word template support)
- Excel sheet with certificate data
- Certificate template with placeholder tags (e.g., `<<Name>>`, `<<Course>>`)

---

## 🚀 Getting Started

1. Clone or download this repository.
2. Open `Main.xaml` in UiPath Studio.
3. Ensure your template and Excel file paths are correctly configured.
4. Run the process to generate certificates.


---

## 🙋‍♂️ Author

Tarun Magaji – [GitHub Profile](https://github.com/yourusername)

---

## 💡 Tips

- You can extend this project to send certificates via email using the included Mail activities.
- Add more personalization fields as needed by modifying the template and Excel input.

