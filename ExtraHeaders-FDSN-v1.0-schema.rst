 

.. _ExtraHeaders-FDSN-v1.0.schema.json#/:

ExtraHeaders-FDSN-v1.0.schema
=============================

Extra headers in miniSEED 3 data format

:type: ``object``

:Schema: ``http://json-schema.org/draft-07/schema#``

:id: ``http://www.fdsn.org/schemas/ExtraHeaders-FDSN-v1.0.schema.json``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/definitions:

definitions
***********


.. _ExtraHeaders-FDSN-v1.0.schema.json#/definitions/Equipment:

Equipment
+++++++++

:type: ``object``

:Additional properties allowed: ``No``

**Properties:** :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/definitions/Equipment/properties/Model`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/definitions/Equipment/properties/Serial`


.. _ExtraHeaders-FDSN-v1.0.schema.json#/definitions/Equipment/properties/Model:

Model
#####

Model of equipment

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/definitions/Equipment/properties/Serial:

Serial
######

Serial number of equipment

:type: ``string``

**Properties:** :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN`


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN:

FDSN
++++

Reserved extra headers defined by the FDSN

:type: ``object``

:Additional properties allowed: ``No``

**Properties:** :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Clock`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/DataQuality`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Logger`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/ProvenanceURI`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Recenter`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Sensor`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Sequence`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time`


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration:

Calibration
###########

Headers related to calibrations

:type: ``object``

:Additional properties allowed: ``No``

**Properties:** :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence`


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence:

Sequence
>>>>>>>>

List of calibration sequences

:type: ``array``

.. container:: sub-title

 Every element of **Sequence**  is:

List of calibrations

:type: ``object``

:Additional properties allowed: ``No``

**Properties:** :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Amplitude`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/AmplitudeRange`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/BeginTime`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Continued`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Coupling`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Duration`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/EndTime`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/InputChannel`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/InputUnits`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Noise`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/ReferenceAmplitude`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Rolloff`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/SinePeriod`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/StepAlternateSign`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/StepBetween`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/StepFirstPulsePositive`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Steps`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Trigger`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Type`


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Amplitude:

Amplitude
.........

Amplitude of calibration signal.  For pseudo-random calibrations, this should be the peak-to-peak amplitude of the steps. [same as SEED 2.4 Blockettes 300,310, field 8 and Blockettes 320,390, field 7]

:type: ``number``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/AmplitudeRange:

AmplitudeRange
..............

Amplitude range of calibration, use values of PEAKTOPEAK, ZEROTOPEAK, RMS OR RANDOM. [same as SEED 2.4 Blockette 310, field 5, bits 4,5,6 and Blockette 320, field 5, bit 4]

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/BeginTime:

BeginTime
.........

Calibration begin time. [similar to SEED 2.4 Blockettes 300,310,320,390, field 3]

:type: ``string``

:format: ``date-time``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Continued:

Continued
.........

Calibration is continued from previous records. [same as SEED 2.4 Blockettes 300,310,320,390, field 5, bit 3]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Coupling:

Coupling
........

Coupling of the calibration signal, such as RESISTIVE or CAPACITIVE. [same as SEED 2.4 Blockettes 300,310, field 12 and Blockette 320, field 11]

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Duration:

Duration
........

Duration of calibration in seconds. For step calibrations this is the duration of the step.  [same as SEED 2.4 Blockettes 300,310,320,390, field 6]

:type: ``number``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/EndTime:

EndTime
.......

Calibration end time. [same as SEED 2.4 Blockette 395, field 3]

:type: ``string``

:format: ``date-time``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/InputChannel:

InputChannel
............

Channel containing the calibration input. [same as SEED 2.4 Blockettes 300,310, field 9 and Blockettes 320,390, field 8]

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/InputUnits:

InputUnits
..........

Units of calibration input, usually volts or amps. [same as SEED 2.4 Blockette 52, field 9]

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Noise:

Noise
.....

Noise characteristics for pseudo-random calibrations, such as WHITE or RED. [same as SEED 2.4 Blockette 320, field 13]

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/ReferenceAmplitude:

ReferenceAmplitude
..................

Reference amplitude.  This is a user-defined value that indicates either the voltage or amperage of the calibration signal when the calibrator is set to 0dB. [same as SEED 2.4 Blockettes 300,310, field 11 and Blockette 320, field 10]

:type: ``number``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Rolloff:

Rolloff
.......

Rolloff characteristics for any filters used on the calibrator, such as 3dB@10Hz.  [same as SEED 2.4 Blockettes 300,310, field 13 and Blockette 320, field 12]

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/SinePeriod:

SinePeriod
..........

Period of sine calibrations in seconds. [same as SEED 2.4 Blockette 310, field 7]

:type: ``number``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/StepAlternateSign:

StepAlternateSign
.................

Step calibration alternate sign.  [same as SEED 2.4 Blockettes 300, field 5, bit 1]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/StepBetween:

StepBetween
...........

Interval between times a step calibration is on in seconds. [same as SEED 2.4 Blockette 300, field 7]

:type: ``number``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/StepFirstPulsePositive:

StepFirstPulsePositive
......................

Step calibration, first pulse is positive. [same as SEED 2.4 Blockette 300, field 5, bit 0]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Steps:

Steps
.....

Number of step calibrations in sequence. [same as SEED 2.4 Blockette 300, field 4]

:type: ``number``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Trigger:

Trigger
.......

Calibration trigger, use AUTOMATIC or MANUAL. [same as SEED 2.4 Blockettes 300,310,320,390, field 5, bit 2]

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Calibration/properties/Sequence/items/properties/Type:

Type
....

Type of calibration: STEP, SINE, PSEUDORANDOM, GENERIC.

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Clock:

Clock
#####

Description of clock system

:Reference: :ref:`Equipment#/`


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/DataQuality:

DataQuality
###########

Data quality indicator, use D, R, Q or M. [same as SEED 2.4 FSDH, field 2]

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event:

Event
#####

Headers related to event detection and progression

:type: ``object``

:Additional properties allowed: ``No``

**Properties:** :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Begin`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/End`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/InProgress`


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Begin:

Begin
>>>>>

An event starts in this record. [same as SEED 2.4 FSDH, field 12, bit 2]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection:

Detection
>>>>>>>>>

List of event detections

:type: ``array``

.. container:: sub-title

 Every element of **Detection**  is:

:type: ``object``

:Additional properties allowed: ``No``

**Properties:** :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/BackgroundEstimate`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/Detector`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/MEDLookback`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/MEDPickAlgorithm`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/MEDSNR`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/OnsetTime`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/SignalAmplitude`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/SignalPeriod`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/Type`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/Units`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/Wave`


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/BackgroundEstimate:

BackgroundEstimate
..................

Event background estimate in counts. [same as SEED 2.4 Blockettews 200 and 201, field 5]

:type: ``number``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/Detector:

Detector
........

Name of the event detector. [same as SEED 2.4 Blockette 200, field 9 and Blockette 201, field 12]

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/MEDLookback:

MEDLookback
...........

Murdock event detction lookback value: 0, 1 or 2. [same as SEED 2.4 Blockette 201, field 10]

:type: ``integer``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/MEDPickAlgorithm:

MEDPickAlgorithm
................

Murdock event detection pick algorithm: 0 or 1. [same as SEED 2.4 Blockette 201, field 11]

:type: ``integer``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/MEDSNR:

MEDSNR
......

Murdock event detection signal-to-noise ratios. [same as SEED 2.4 Blockette 201, field 9]

:type: ``array``

.. container:: sub-title

 Every element of **MEDSNR**  is:

:type: ``number``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/OnsetTime:

OnsetTime
.........

Event signal onset time. [same as SEED 2.4 Blockettews 200 and 201, field 8]

:type: ``string``

:format: ``date-time``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/SignalAmplitude:

SignalAmplitude
...............

Event amplitude of signal in counts. [same as SEED 2.4 Blockettews 200 and 201, field 3]

:type: ``number``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/SignalPeriod:

SignalPeriod
............

Event period of signal in seconds. [same as SEED 2.4 Blockettews 200 and 201, field 4]

:type: ``number``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/Type:

Type
....

Type of event detection, e.g. MURDOCK

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/Units:

Units
.....

Units of amplitude band background estimate, use COUNTS for unprocessed signal. [similar to SEED 2.4 Blockettews 200, field 6, bit 1]

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/Detection/items/properties/Wave:

Wave
....

Event detection wave, use values of DILATATION or COMPRESSION if determined. [same as SEED 2.4 Blockettews 200 and 201, field 6, bit 0]

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/End:

End
>>>

An in-progress event ends in this record, i.e. the detection algorithm de-triggers. [same as SEED 2.4 FSDH, field 12, bit 3]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Event/properties/InProgress:

InProgress
>>>>>>>>>>

An event is in progress. [same as SEED 2.4 FSDH, field 12, bit 6]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags:

Flags
#####

:type: ``object``

:Additional properties allowed: ``No``

**Properties:** :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/AmplifierSaturation`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/DigitizerClipping`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/EndOfTimeSeries`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/FilterCharging`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/Glitches`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/LongRecordRead`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/MassPositionOffscale`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/MissingData`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/ShortRecordRead`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/Spikes`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/StartOfTimeSeries`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/StationVolumeParityError`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/TelemetrySyncError`


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/AmplifierSaturation:

AmplifierSaturation
>>>>>>>>>>>>>>>>>>>

Amplifier saturation detected. [same as SEED 2.4 FSDH, field 14, bit 0]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/DigitizerClipping:

DigitizerClipping
>>>>>>>>>>>>>>>>>

Digitizer clipping detected. [same as SEED 2.4 FSDH, field 14, bit 1]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/EndOfTimeSeries:

EndOfTimeSeries
>>>>>>>>>>>>>>>

DEPRECATED End of time series. [same as SEED 2.4 FDSH, field 13, bit 4]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/FilterCharging:

FilterCharging
>>>>>>>>>>>>>>

A digital filter may be charging. [same as SEED 2.4 FDSH, field 14, bit 6]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/Glitches:

Glitches
>>>>>>>>

Glitches detected. [same as SEED 2.4 FSDH, field 14, bit 3]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/LongRecordRead:

LongRecordRead
>>>>>>>>>>>>>>

DEPRECATED Long record read (possibly no problem). [same as SEED 2.4 FDSH, field 13, bit 1]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/MassPositionOffscale:

MassPositionOffscale
>>>>>>>>>>>>>>>>>>>>

Sensor mass position is offscale as defined by the vendor or operator.

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/MissingData:

MissingData
>>>>>>>>>>>

DEPRECATED Missing data. [same as SEED 2.4 FDSH, field 14, bit 4]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/ShortRecordRead:

ShortRecordRead
>>>>>>>>>>>>>>>

DEPRECATED Short record read (record padded). [same as SEED 2.4 FDSH, field 13, bit 2]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/Spikes:

Spikes
>>>>>>

Spikes detected. [same as SEED 2.4 FSDH, field 14, bit 2]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/StartOfTimeSeries:

StartOfTimeSeries
>>>>>>>>>>>>>>>>>

DEPRECATED Start of time series. [same as SEED 2.4 FDSH, field 13, bit 3]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/StationVolumeParityError:

StationVolumeParityError
>>>>>>>>>>>>>>>>>>>>>>>>

DEPRECATED Station volume parity error possibly present. [same as SEED 2.4 FDSH, field 13, bit 0]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Flags/properties/TelemetrySyncError:

TelemetrySyncError
>>>>>>>>>>>>>>>>>>

DEPRECATED Telemetry synchronization error. [same as SEED 2.4 FDSH, field 14, bit 5]

:type: ``boolean``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Logger:

Logger
######

Description of data logger

:Reference: :ref:`Equipment#/`


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/ProvenanceURI:

ProvenanceURI
#############

An identifier for a provenance description

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Recenter:

Recenter
########

Headers related to sensor recentering (mass, gimble, etc.)

:type: ``object``

:Additional properties allowed: ``No``

**Properties:** :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Recenter/properties/Sequence`


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Recenter/properties/Sequence:

Sequence
>>>>>>>>

List of recentering sequences

:type: ``array``

.. container:: sub-title

 Every element of **Sequence**  is:

List of recenterings

:type: ``object``

:Additional properties allowed: ``No``

**Properties:** :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Recenter/properties/Sequence/items/properties/BeginTime`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Recenter/properties/Sequence/items/properties/EndTime`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Recenter/properties/Sequence/items/properties/Trigger`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Recenter/properties/Sequence/items/properties/Type`


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Recenter/properties/Sequence/items/properties/BeginTime:

BeginTime
.........

Recenter begin time.

:type: ``string``

:format: ``date-time``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Recenter/properties/Sequence/items/properties/EndTime:

EndTime
.......

Estimate of recenter end time.

:type: ``string``

:format: ``date-time``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Recenter/properties/Sequence/items/properties/Trigger:

Trigger
.......

Calibration trigger, use AUTOMATIC or MANUAL.

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Recenter/properties/Sequence/items/properties/Type:

Type
....

Type of recenter: Mass, Gimbal, etc.  If omitted a mass recenter may be assumed.

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Sensor:

Sensor
######

Description of sensor

:Reference: :ref:`Equipment#/`


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Sequence:

Sequence
########

Data record sequence number. [same as SEED 2.4 FSDH, field 1]

:type: ``integer``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time:

Time
####

Headers related to data timing and recording system clock

:type: ``object``

:Additional properties allowed: ``No``

**Properties:** :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Correction`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Exception`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/LeapSecond`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/MaxEstimatedError`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Quality`


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Correction:

Correction
>>>>>>>>>>

Time correction applied to record start time in seconds. [same as SEED 2.4 FSDH, field 16]

:type: ``number``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Exception:

Exception
>>>>>>>>>

List of timing exceptions

:type: ``array``

.. container:: sub-title

 Every element of **Exception**  is:

:type: ``object``

:Additional properties allowed: ``No``

**Properties:** :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Exception/items/properties/ClockStatus`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Exception/items/properties/Count`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Exception/items/properties/ReceptionQuality`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Exception/items/properties/Time`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Exception/items/properties/Type`, :ref:`ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Exception/items/properties/VCOCorrection`


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Exception/items/properties/ClockStatus:

ClockStatus
...........

Description of clock status, clock specific parameters such as the station for an Omega clock or satellite signal to noise ratios for GPS clocks. [same as SEED 2.4 Blockette 500, field 10]

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Exception/items/properties/Count:

Count
.....

Exception count, with meaning based on type of exception, such as 15 missing time marks.  [same as SEED 2.4 Blockette 500, field 7]

:type: ``integer``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Exception/items/properties/ReceptionQuality:

ReceptionQuality
................

Reception quality as a percent of maximum clock accuracy based only on information from the clock. [same as SEED 2.4 Blockette 500, field 6]

:type: ``integer``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Exception/items/properties/Time:

Time
....

Time of timing exeption. [same as SEED 2.4 Blockette 500, field 4]

:type: ``string``

:format: ``date-time``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Exception/items/properties/Type:

Type
....

Description of clock exception, such as MISSING TIMEMARK. [same as SEED 2.4 Blockette 500, field 8]

:type: ``string``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Exception/items/properties/VCOCorrection:

VCOCorrection
.............

VCO correction, a percentage from 0 to 100% of VCO control value, where 0 is the slowest and 100 is the fastest.  [same as SEED 204 Blockette 500, field 3]

:type: ``number``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/LeapSecond:

LeapSecond
>>>>>>>>>>

If present, one or more leap seconds occuring during this record.  The value specifies the number of leap seconds and direction.  For example, use 1 to specify a single positive leap second and -1 to specify a single negative leap second. [incorporates SEED 2.4 FSDH, field 12, bits 4 and 5]

:type: ``integer``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/MaxEstimatedError:

MaxEstimatedError
>>>>>>>>>>>>>>>>>

Maximum estimated timing error in seconds.

:type: ``number``


.. _ExtraHeaders-FDSN-v1.0.schema.json#/properties/FDSN/properties/Time/properties/Quality:

Quality
>>>>>>>

Timing quality.  A vendor specific value from 0 to 100% of maximum accuracy. [same as SEED 2.4 Blockette 1001, field 3]

:type: ``number``
