# Campus Automated Lighting System

**Thiruppathi P | Team Lead**  
**Service-learning project | CHRIST (Deemed to be University), Kengeri Campus**

## Purpose and location

The project introduced motion-based lighting control across the entire fourth floor of Block 3. Its purpose was to reduce unnecessary lighting operation while making lighting available when people move through the monitored areas.

## Implementation

Approximately 8 PIR motion sensors with built-in relays control 16 lights. The sensors are integrated into the building's lighting circuits. Motion activates the associated lights; following approximately 15 minutes without detected movement, the lights switch off.

The system operates without a microcontroller. Switching and delay behavior are handled by the PIR sensor units, so no custom firmware is required.

## Team leadership and engineering work

I led the project team and handled sensor integration and wiring in the campus building. A teammate and I jointly created the Tinkercad circuit design. The team carried out the physical installation across the floor.

![Campus installation work](../media/installation-04.jpg)

## Design development

The Tinkercad screenshots show a conceptual arrangement of PIR sensing, relay switching and lighting loads. Separate relay components are represented in the model; the installed PIR units incorporate their relays. The diagrams are retained as design-development material rather than instructions for reproducing the building's electrical installation.

![Conceptual Tinkercad layout](../diagrams/tinkercad-layout.png)

## Functional testing and outcome

The installation successfully switched the lights on in response to movement and switched them off after the inactivity delay. The complete floor was covered by approximately 8 sensors controlling 16 lights. The university found the installation useful.

| Installation characteristic | Result |
|---|---|
| Coverage | Entire floor |
| Sensor count | Approximately 8 |
| Lights controlled | 16 |
| Inactivity delay | Approximately 15 minutes |
| Motion activation and timed switch-off | Successful |
| University feedback | Found useful |

## Engineering considerations

PIR sensors respond to movement rather than continuously detecting stationary occupants. Placement, coverage and the chosen delay therefore affect user experience. The project uses an approximately 15-minute delay to keep the lighting active between detected movements.

## Future improvements

Potential extensions include measuring lighting energy consumption before and after automation, reviewing coverage as the floor layout changes, and evaluating daylight-based control. These are future improvements.

## Report edition

This portfolio edition focuses on the installed lighting system and its final configuration. It replaces conflicting draft delay values with the approximately 15-minute setting and distinguishes the Tinkercad concept from the built-in-relay installation. Student registration numbers and unrelated report sections are excluded.
