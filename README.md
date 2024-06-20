# Follow Joly Roger Vessel
Test sur une API en temps reel de tracking de bateau via AIS 
- AIS Automatic Identification System
- This is an automatic tracking system that uses transponders on ships to locate them.
- Track ship movements, monitor maritime accidents and discover ship's cargo from aisstream.io's websocket api in real-time and for free.
- https://aiitream.io
- Live AIS data for most of the globe is available for free.
- The catch is the data is delivered via WebSocket
- https://aisstream.io/documentation
- aistream.io is websocket api that allows a user to stream maritime data such as
  - a ship's positions,
  - direction of travel,
  - and much more.
 
## Api Key
- https://aisstream.io/apikeys

## Github
- https://github.com/aisstream

# Python example
- mkdir FollowJolyRogerVessel
- cd FollowJolyRogerVessel
- Clone the repository: `git clone https://github.com/aisstream/example`
- Navigate to the python directory: `cd example/python`
- Create Virtual Environment: `python -m venv .venv`
- Activate Virtuel Environment: `.venv\Scripts\activate`
- creation du fichier requirements.txt a partir du fichier setup.py
- `pip install -r requirements.txt`
- Replace "<YOUR API KEY>" in the main.py file with your AISStream API key
- Run the example: `python main.py`
