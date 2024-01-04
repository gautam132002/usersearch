# UserSearch
![Display_unibe](https://img.shields.io/badge/Application%20Type-Streamlit-informational?style=flat&logo=streamlit&logoColor=white&color=red)


UserSearch is a simple web application that allows users to search for specific individuals within two different datasets: OSF (Open Science Framework) and BORIS (Behavioral Observation Research Interactive Software). Users can enter a person's name in the search bar to retrieve relevant data about the individual from the selected dataset. If no name is specified, the application will load the entire dataset or table.

## Selecting Dataset

You can choose between two datasets: OSF and BORIS.

- **OSF**: This dataset contains public records, and the application will load the data table when selected. However, it will not draw any graphs as no graph data is available for private records.

- **BORIS**: When BORIS dataset is selected, the application will not only load the data table but also generate graphs in the form of scatter plots and line charts based on the available data.

## How to Run

### Online Deployed Version

You can access the online deployed version of UserSearch by visiting the following link: [https://usersearchdashboard.streamlit.app/](https://usersearchdashboard.streamlit.app/)

### Manual Execution

If you prefer to run UserSearch locally, follow these steps:

1. Install the required dependencies by executing the following command in your terminal or command prompt:

   ```
   pip install -r requirements.txt
   ```

2. Run the application using Streamlit by executing the following command:

   ```
   streamlit run usersearch_app.py
   ```

## Contribution

Contributions to UserSearch are welcome! If you would like to contribute, please follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch with a descriptive name for your feature or bug fix.
3. Make your changes and commit them with clear and concise messages.
4. Push your branch to your forked repository.
5. Submit a pull request to the main repository, describing the changes you made.

## Contact

If you have any questions, suggestions, or concerns regarding UserSearch, feel free to reach out to me at gautamnegu0202@protonmail.com. I would be happy to hear from you!
