# **Task 1 — Model selection worksheet**

## Brief A : Aegis Flight-Control Software Update 
### Chosen model: Waterfall

| Criteria | Justification |
|---|---|
| Requirement stability | Requirements are very well understood and stable. The failure mode and required warning behaviour are precisely specified before development begins. |
| Risk/safety | This is safety-critical software. A defect could endanger lives, so a highly structured process with extensive verification and documentation is appropriate. |
| Timeline | There is no major pressure for a rapid release. Certification timelines of 12–18 months dominate the schedule, so a sequential process is suitable. |
| Customer involvement | The client has a large quality-assurance department and expects extensive documentation at every stage rather than continuous changes to requirements. |
| Documentation | Complete traceability from requirements through code to testing evidence is required for certification. Waterfall supports clearly defined stages and documentation. |

**Risk of waterfall:**
If a requirement were discovered to be wrong later in development, making changes could be expensive and time-consuming because the process is sequential.

**Justification:**
Waterfall is appropriate because the requirements are stable, the project is safety-critical, extensive documentation and traceability are required, and there is no need for rapid releases.


## Brief B : Riverside Bakery Marketing Website 
### Chosen model: RAD (Rapid Application Development)

| Criteria | Justification |
|---|---|
| Requirement stability | Requirements are not stable. The owner is unsure what the website should look like and changes visual details after seeing working drafts. |
| Risk/safety | There is no safety or regulatory risk, and the technical complexity is low. |
| Timeline | The website needs to be live within three weeks, so rapid development is important. |
| Customer involvement | The owner can provide feedback almost daily, making frequent customer feedback and iterations practical. |
| Documentation | Extensive documentation is not a major requirement for this simple website. |

**Risk of RAD:**
The frequent changes and rapid development could result in scope creep or a less polished final website if too many changes are made close to the deadline.

**Justification:**
RAD fits because the project has a short deadline, low technical and safety risk, an involved customer, and requirements that can be refined through working prototypes.

## Project C : CampusCircle Community App
### Chosen model: Incremental

| Criteria | Justification |
|---|---|
| Requirement stability | Requirements are expected to change significantly once students start using early versions of the app. |
| Risk/safety | There is no formal regulatory requirement. Basic data protection is expected, but the project does not have the safety-critical risks of the flight-control system. |
| Timeline | The team wants a usable version within one month and needs to launch before the next academic term. |
| Customer/end-user involvement | The founders specifically want to adapt the app based on real student behaviour and feedback. |
| Development approach | Features such as browsing clubs, event RSVP and chat can be developed and released incrementally rather than specifying the entire application upfront. |

**Risk of Incremental:**
Changing requirements between increments could lead to inconsistent design or technical problems if the team does not maintain a clear overall architecture.

**Justification:**
Incremental development is suitable because the team wants to release a usable version quickly and then improve the application based on real user feedback. This matches the brief's expectation that features will evolve after students begin using early versions.

# Final Selections
| Project | Process model | Main reason |
|---|---|---|
| Aegis Flight-Control | **Waterfall** | Stable requirements, safety-critical, extensive documentation |
| Riverside Bakery | **RAD** | Three-week deadline, low complexity, frequent customer feedback |
| CampusCircle | **Incremental** | Rapid initial release with requirements evolving through user feedback |

# Task 2 - Share and challenge 
### CampusCircle Community App — Incremental Model

For the CampusCircle Community App, I chose the **Incremental process model**.
The main reason is that the requirements are expected to change. The founders have a rough idea of the features, but they want to see how students use the app before deciding exactly what should be developed.
The team also wants a usable version within one month, so developing the app in smaller increments allows them to release features quickly and improve them based on feedback.
There is no major safety or regulatory risk, although basic data protection is required.
One risk is that frequent changes could make the system difficult to manage if the team doesn't maintain a clear overall structure.
I chose Incremental because it allows the team to release a working product quickly while adapting it based on real user feedback.

#### **Challenge question**
**Why wouldn't you use RAD instead, since the team has a short deadline and wants frequent feedback?**  
RAD would also fit some characteristics of the project, particularly the short timeline and user feedback.
However, I chose Incremental because the brief specifically describes an application whose features are expected to change significantly after students use early versions.
Incremental development directly supports releasing functionality in stages and adapting later increments based on what is learned.

# Task 3 — Portfolio entry 
## Process Model Justification

I would use the **Incremental process model** for a university student study-planning application. The app would allow students to create study schedules, set reminders and track their progress. 
I would choose Incremental because the requirements could change based on feedback from students using the application. 
Instead of developing everything at once, the team could release the basic scheduling features first and then gradually add reminders and progress tracking. 
This would allow students to use the app early and provide feedback that could be used to improve later versions. It would also allow the team to identify problems earlier rather than waiting until the whole application was finished.
The main risk is that frequent changes could make the system harder to manage or cause inconsistencies between features. To reduce this risk, the team would need to maintain a clear overall structure. 
Overall, Incremental provides flexibility while allowing useful software to be delivered in stages.

### Task 2 Reflection

For Task 2, I presented my choice of the **Incremental model** for the CampusCircle app. 
A classmate suggested RAD because of the short deadline and frequent feedback. 
I explained that I chose Incremental because the app is expected to change based on user feedback.
