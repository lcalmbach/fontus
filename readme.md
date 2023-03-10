Fontus is an web application allowing users to create beautiful [Piper-diagrams](https://en.wikipedia.org/wiki/Piper_diagram). The app includes a demo dataset, but users may upload their own data. The application written in Python using the Streamlit framework and the Bokeh graphic library. You can use the [online version](https://lcalmbach-pyper-app-netzym.streamlit.app/) or install the app locally on your machine. Fontus is designed to be extended with further plots and analyis options if there is sufficient interest. Don't hesitate to contact the [author](lcalmbach@gmail.com) either on github or by mail if you encounter issues or if you have suggestions.

To install the app locally proceed as follows (on Windows system):
```
> git clone https://github.com/lcalmbach/PyPER
> cd PyPER
> python -m venv env
> env\scripts\activate
> pip install -r requirements.txt
> streamlit run app.py
```