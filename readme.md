# python-electron-boilerplate
python-electron-boilerplate is a boilerplate framework allowing you to create a multi-process application using Python as a backend and Node.JS and Electron on the frontend. ZeroMQ sockets are used to create communication channels. This is very barebones and merely displays the functionality that ZMQ can offer to communicate between processes.
![Boilerplate](https://i.imgur.com/T7CyAk4.png)

## Installing
Tested with node v20.7.0 and Python 3.11.6

### Frontend / Electron
```
cd frontend && npm i
```

### Backend / Python / ZMQ
```
pip3 install pyzmq # uses version 25.1.2
```

## Running
Run app.py in the backend, and then start electron in the frontend directory.
```
# process / terminal 1
cd frontend && npm start

# process / terminal 2
cd backend && python3 app.py
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
