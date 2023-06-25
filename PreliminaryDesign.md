Preliminary Design Documentation

*24/06/2023*

Product Overview:

- The product is a smart lock designed for standard residential doors.
- The lock's primary method of operation is based on the proximity of a designated smart key fob.
- Communication between the smart key fob and the smart lock is achieved via secure Bluetooth technology.
- Energy efficiency is a key design feature, with the system designed to minimize energy use and prevent premature battery drain in both the fob and lock.
- Proximity alone does not trigger unlocking. The user must also engage a touch sensor on the door handle, which, when fully depressed, activates the unlocking mechanism.
- Locking can occur in one of two ways, depending on the final design: either an upward pull of the handle immediately locks the door, or the door locks automatically when the fob moves out of range.
- From the inside, the door unlocks automatically when the handle is touched, allowing it to be fully depressed and opened.

Critical Design Considerations:

- The system must prevent unintended unlocking when the fob is inside the house and near the door.
- Directional antennas are a proposed solution to limit the lock's field of view, preventing it from detecting the fob through walls.
- Security and user-friendly mechanisms are key design features.

Additional Features:

- An accompanying app, compatible with both iPhone and Android, will be developed to provide users with an interface for customising settings and preferences.
- The user's phone can function as a secondary access device, with unlocking capabilities via the app or NFC.
- For the initial prototyping phase, a Raspberry Pi will serve as the lock's control centre.

Practical Design Considerations:

- Backup Entry Methods: In the event of a lost fob or drained battery, alternative entry methods should be available.
- Remote Access: The system should be designed with the potential for integration with home automation systems, or include built-in remote access capabilities.
- Activity Log: An activity log should be implemented within the app to track lock and unlock events.
- Guest Access: The app should include a feature for granting temporary access to guests.
- Tamper Alerts: An alert system should be put in place to notify the user of any attempts to tamper with the lock or force the door open.
- Battery Life Indicators: Indicators should be provided (on the lock itself or within the app) to alert users when the batteries in the lock or the fob need to be replaced.
- Automatic Locking: An automatic locking feature should be considered that activates a certain period of time after the door has been closed.
- Weatherproofing: The exterior components of the lock must be able to withstand various weather conditions.
- Compliance with Regulations: The design and functionality of the product must adhere to all local and national regulations pertaining to electronic locks and home security systems.
- User-Friendly Installation: The system should be designed for easy installation, accompanied by clear instructions or an installation guide video.
