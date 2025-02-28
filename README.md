# Trip Trak

## Overview

django_trip_trak is a web application designed to help users plan and track their trips. It allows users to create and manage trips, add notes, and upload images related to their travels.

## Features

- **User Authentication**: Secure user registration and login system.
- **Trip Management**: Create, update, and delete trips with details like city, country, start date, and end date.
- **Notes**: Add notes to trips with descriptions, images, and ratings.
- **Responsive Design**: Mobile-friendly interface using Tailwind CSS.

## Installation

1. **Clone the repository**:
   \`\`\`bash
   git clone $GITHUB_REPO
   cd $PROJECT_NAME
   \`\`\`

2. **Set up the virtual environment**:
   \`\`\`bash
   python3 -m venv env
   source env/bin/activate
   \`\`\`

3. **Install dependencies**:
   \`\`\`bash
   pip install -r requirements.txt
   \`\`\`

4. **Apply migrations**:
   \`\`\`bash
   python manage.py migrate
   \`\`\`

5. **Run the development server**:
   \`\`\`bash
   python manage.py runserver
   \`\`\`

## Usage

- **Register**: Create a new account.
- **Login**: Access your account.
- **Create Trip**: Add a new trip with relevant details.
- **Add Notes**: Attach notes and images to your trips.
- **View Trips**: Browse through your planned trips and associated notes.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
