# User Activity Data Generator and Database Loader

This Python script generates random user activity data and loads it into a PostgreSQL database table.

## Setup

1. Ensure Python 3.x is installed on your system.

2. Install required libraries:
   - pandas
   - numpy
   - sqlalchemy

3. Create a PostgreSQL database and obtain the connection string.

4. Clone the repository.

5. Create a `.env` file with your PostgreSQL connection string.

## Usage

Run the script. The generated data will be loaded into the `user_activity` table in your PostgreSQL database.

## Description

- Generates random data for user activity metrics.
- Calculates end users, active users, monthly retention rates, and churn.
- Writes data to a PostgreSQL database table.

## Contributing

Contributions are welcome! Open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
