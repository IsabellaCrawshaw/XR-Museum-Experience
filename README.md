# Mixed-Reality Museum Experience

A collaborative mixed-reality museum experience that connects physical artefact exploration with an immersive AR reconstruction activity. Visitors collect artefacts, collaborate in real time to recreate historical spaces, and engage with past recreations through interactive social features.

---

## 📌 Overview

This project transforms a traditional museum visit into a shared, interactive experience. Visitors first explore artefacts in the museum, scanning QR codes to collect items and share reflections. These artefacts are later used in an AR environment where groups collaboratively reconstruct a historical building at the Keighton site.

The design builds on the idea that museum visitors seek meaningful, social experiences, achieved through connections with artefacts and other visitors.

---

## 🧭 Experience Flow

1. **Museum Tour & Artefact Collection**
   - Visitors view Keighton artefacts and others from a similar period.
   - QR codes allow visitors to scan and add artefacts to their personal collection.
   - Users can share thoughts on artefacts with the group, helping establish common ground and trust.

2. **Group AR Reconstruction at Keighton**
   - After the tour, the group moves to the Keighton site.
   - Each participant is assigned a room within a historical building.
   - Through AR on their phones, they see a bare-bones room and place collected artefacts to bring it to life.
   - Manipulations are private until confirmed, giving performers control over when their changes are revealed.

3. **Completion, Exploration & Voting**
   - Once all rooms are submitted, the completed building becomes available for others to visit.
   - Visitors can explore rooms, act as spectators, and vote on the best recreation.
   - Competition is introduced while keeping collaboration as the core focus.

---

## 🎭 Roles: Performer, Spectator & Bystander

### Performers
- Actively manipulate the AR room by placing artefacts.
- See immediate effects of their actions and control when they are revealed.
- Can attach comments to artefacts, enabling written communication with others.
- Movement around the AR room is public via a cursor, supporting location awareness.
- Can transfer collected artefacts to other users to support collaboration.

### Spectators
- Can visit other group members’ rooms at any time.
- See confirmed artefact placements but not the performer’s private selection phase.
- May be granted permission to become co-performers and help with the room.
- Can see which artefacts were placed by whom, supporting reciprocal awareness.

### Bystanders
- Await their turn to recreate, with anticipation built through screens showing performers’ manipulations.
- Once it is their group’s turn, they select a building and assign rooms.
- Use headsets playing sounds of Keighton to increase immersion and support location-based calling and verbal communication.

---

## 🕶️ AR Recreations Design

- Participants collaborate **at the same time, in different places (STDP)** as each works on an individual AR room.
- **Same Time, Same Place (STSP)** occurs when group members co-create in the same room.
- Group progress is visible through a tracker so participants can see who has finished.
- Screens reveal parts of performers’ actions, building suspense while preserving privacy until confirmation.

---

## 🗺️ Past Recreations Design

- Supports **Different Time, Same Place (DTSP)** interaction.
- Visitors explore past recreations as anonymous interactive spectators in **“Ghost Mode”**.
- Room designers’ identities are hidden by default for privacy.
- Artefacts with comments are highlighted with visual markers, guiding visitors toward points of interest.
- Comments are location-tagged using GPS.
- Users can:
  - Read comments attached to artefacts.
  - Message the room designer asynchronously.
  - Reveal identities mutually once trust is built.
  - Vote on whether a recreation is the best, adding a competitive, non-verbal feedback element.

---

## 💬 Messages Design

- Supports **Different Time, Different Place (DTDP)** communication.
- A message screen enables users who first met in person to stay connected afterwards (e.g., from home).
- Allows ongoing reflection, discussion of recreations, and relationship-building beyond the museum visit.

---

## 📱 Mobile Collocated Interaction Design Framework

### Social Perspective
- Core focus on collaboration: users recreate the building together and may co-create within rooms.
- Communication is supported through features like calling and messaging.
- Competition (e.g., voting on best recreations) is secondary to collaboration.

### Technological Perspective
- **Information Symmetry**
  - Symmetrical: all users can see the positions of others in the AR space.
  - Asymmetrical: only the performer sees artefacts and placement before confirmation.
- **Interaction Abilities**
  - Symmetrical when each participant works within their own room.
  - Asymmetrical when acting as spectators in others’ rooms, with abilities depending on permissions.
- **Information Distribution**
  - Information is revealed after artefact placement is confirmed by the performer.

### Spatial Perspective
- Movement is inherent: participants walk through the museum, around the AR site, and between rooms.
- AR rooms have boundaries defined by sensors mapped onto the floor.
- Proximity (via GPS and device position) drives:
  - Ability to interact with artefacts.
  - Location-based calling and communication.
  - Events such as transforming spectators into performers or warning users when leaving the room/building.

### Temporal Perspective
- Synchronisation is user-driven, with participants working at their own pace.
- Engagement is intermittent: museum tour, AR recreation, exploration of past recreations, and later messaging.
- Seeing group progress can encourage slower participants to speed up.

---

## 🧪 Prototype Notes

- Navigation bar elements are ordered according to expected usage to support intuitive mapping.
- Screen titles are removed from the navigation bar and used as visual markers of the user’s current location.
- Real-time feedback helps maintain transparency so users can see the results of their actions.
- AR prototype buttons for navigation are included for testing but may not appear in the final design.

---

## 📚 Academic References

- Reeves, S., Benford, S., O’Malley, C. and Fraser, M. (2005). *Designing the spectator experience.* Proceedings of the SIGCHI Conference on Human Factors in Computing Systems.  
- Lacoche, J., Pallamin, N., Boggini, T. and Royan, J. (2017). *Collaborators awareness for user cohabitation in co-located collaborative virtual environments.* Proceedings of the 23rd ACM Symposium on Virtual Reality Software and Technology.  
- Lundgren, S., Fischer, J.E., Reeves, S. and Torgersson, O. (2015). *Designing Mobile Experiences for Collocated Interaction.* Proceedings of the 18th ACM Conference on Computer Supported Cooperative Work & Social Computing.  
- Ali, S., Bedwell, B. and Koleva, B. (2018). *Exploring relationships between museum artefacts through spatial interaction.* Proceedings of the 10th Nordic Conference on Human-Computer Interaction.

---

## 🔗 Project References

- Boardnoter (2024). Same Time – Same Place (1). COMP3010: Meeting rooms and shared surfaces [6]. University of Nottingham.  
- Firefly (2015). *Drop Messages.* YouTube.  
- Cosley, D., Lewenstein, J., Herman, A., Holloway, J., Baxter, J., Nomua, S., Boehner, K. and Gay, G. *ArtLinks: Fostering Social Awareness and Reflection in Museums.*

