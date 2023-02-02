| [Home](../README.md) |
|----------------------|
# Contents

The **FortiRecon Brand Protection** solution pack contains the following resources.

## Connectors

| Connector Name | Description |
| :-             | :-          |
| Fortinet FortiRecon Brand Protection | Detects typo domain and rouge mobile apps |

## Global Variables

| Global Variable | Description                               |
|:----------------|:------------------------------------------|
| `Demo_mode`     | Enables playbook to execute a mock output |

## Record Sets
| Scenario          | Description |
| :-                | :-          |
|Typo Squatting Domain | Demostrates the scenario where FortiRecon Brand Protection detects a typo squatted domain whose severity score is **High**|
|Rogue Mobile App| Demostrates the scenario where FortiRecon Brand Protection detects a mobile app whose status is **RogueApp** |

## Playbook Collection

| 02 - Use Case - FortiRecon Brand Protection                                 |
|:-------------------------------------------------------------------------|


| Playbook Name                                                          | Description                                                                       |
|:-----------------------------------------------------------------------|:----------------------------------------------------------------------------------|
| Scenario - Fetch Typo Domain                                          | Fetches the list of high-severity typo squatted domains discovered by FortiRecon for the specified organisation and creates alerts for the same |
| Scenario - Fetch Rogue Mobile Apps                                    | Fetches the list of Rogue Mobile Apps discovered by FortiRecon for the specified organisation and creates alerts for the same |
| High Risk Typo Domain Response                                   | Creates a manual task to raise takedown request for high risk typo domain |
| High Risk Rogue Mobile App Response               | Creates a manual task to raise takedown request for high risk rogue mobile app |


>**Warning:** We recommend you clone these playbooks before customizing to avoid information loss while upgrading the solution pack.
