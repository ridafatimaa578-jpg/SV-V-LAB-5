## Task 1: Identify Operations

| OP ID | Operation | Purpose |
| :--- | :--- | :--- |
| **OP-01** | PerformSystemSelfCheck | Verify that all essential sensors and control devices are functioning properly before starting operation. |
| **OP-02** | LoadArtifactProfile | Register artifact ID and load its specific required temperature, humidity, and light environmental limits. |
| **OP-03** | CloseChamberDoor | Secure the conservation chamber door to allow active environmental control to begin. |
| **OP-04** | StartConservation | Transition the system into active conservation mode when the door is closed and the artifact profile is loaded. |
| **OP-05** | AdjustTemperature | Trigger cooling/heating mechanisms when measured temperature drifts outside permitted limits. |
| **OP-06** | AdjustHumidity | Trigger humidification/dehumidification mechanisms when measured humidity drifts outside permitted limits. |
| **OP-07** | VerifyEnvironmentalRecovery | Confirm through sensor feedback that temperature/humidity returned to safe ranges within the allowed time. |
| **OP-08** | InitiateProtectionMode | Switch to protection mode, reduce light, activate backup controls, and alert operators upon recovery failure. |
| **OP-09** | DetectAndHandleVibration | Suspend high-risk operations and enter vibration response mode when significant vibration is detected. |
| **OP-10** | VerifyStabilization | Confirm that vibration levels remain below the threshold for a set stabilization period before resuming normal mode. |
| **OP-11** | HandleDoorOpening | Immediately suspend active conservation activities when the chamber door is opened. |
| **OP-12** | SwitchPowerSource | Switch to emergency power during main power loss, or initiate safe shutdown if emergency power is absent. |
| **OP-13** | AuthorizeArtifactRemoval | Confirm chamber safety and absence of active alerts to allow safe removal of the artifact by an operator. |
