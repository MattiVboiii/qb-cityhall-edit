# qb-cityhall
City Services for QB-Core Framework

## Dependencies
- [qb-core](https://github.com/qbcore-framework/qb-core)
- [PolyZone](https://github.com/mkafrin/PolyZone) - For Interaction (DrawText and qb-target both require this)
- [qb-target](https://github.com/BerkieBb/qb-target) - For Interaction (Optional)
- [qb-phone](https://github.com/qbcore-framework/qb-phone) - For E-Mail

## Features
- Ability to request birth certificate when lost
- Ability to request driver license when granted by a driving instructor
- Ability to request weapon license when granted it by the police
- Ability to apply to government jobs
- Ability to add multiple cityhall locations
- Ability to add nultiple driving school locations
- Ability to take driving lessons
- qb-target integration, this is optional
- PolyZone and qb-core DrawText integration, this is optional

## Screenshots
![image](https://github.com/MattiVboiii/qb-cityhall-edit/assets/57048210/d84e31ea-201d-4d28-a41c-78db7703a6f3)
![image](https://github.com/MattiVboiii/qb-cityhall-edit/assets/57048210/cb3bc540-3fd8-4d51-8965-97cd17723336)
![image](https://github.com/MattiVboiii/qb-cityhall-edit/assets/57048210/1a9786c9-3f5a-4348-b1ad-028cfcb9f057)
![Driving School Sending And Receiving Mail](https://i.imgur.com/iJof4jI.png)
![Driving School DrawText Interaction](https://i.imgur.com/32BPp8f.png)
![Driving School QB-Target Interaction](https://i.imgur.com/P7jWBsV.png)

## Installation
### Manual
- Download the script and put it in the `[qb]` directory.
- Add the following code to your server.cfg/resources.cfg
```
ensure qb-core
ensure qb-target # Optional
ensure qb-phone
ensure qb-cityhall
```

# License

    QBCore Framework
    Copyright (C) 2021 Joshua Eger

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>
