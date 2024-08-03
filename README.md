# Topic Modeling Scientific Papers

This project is a topic modeling of scientific papers using BERTopic transformer and OpenAI API. The dataset
used in this project is a collection of scientific papers from the repository campuss.
The dataset contains 10,000+ scientific papers from 5 different categories study programs. 

The categories are :
- Accounting
- English
- Japanese
- Visual Communication Design
- Management
- Sistem Information
- Electrical Engineering
- Mechanical Engineering
- Civil Engineering
- Industrial Engineering
- Informatics Engineering

## Run Locally

Clone this repository

```bash
  git clone https://github.com/alifnuryana/topic-modeling-karya-tulis.git
```

Go to the project directory

```bash
  cd topic-modeling-karya-tulis
```

Create a new conda environment using the environment.yml file

```bash
  conda env create -f environment.yml
```

Clone the .env.example file and rename it to .env

```bash
  cp .env.example .env
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

- `OPENAI_API_KEY` : API key for representing topic modeling using OpenAI API

## License

[MIT](https://choosealicense.com/licenses/mit/)