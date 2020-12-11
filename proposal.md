<a href="index">Home</a>

# Project Proposal

## Virtual Reality System for Enhancing Oral Health in Young Children
*Cathalina Fontenelle*

### 1. Introduction
Most young children have an incredible fear of visiting the dentist, but it is also difficult to get young children to brush their teeth properly to mitigate frequent trips to the dentist. Studies have shown that teeth decay among children are increasing [1][2]. Untreated decay of primary teeth could lead to serious problems for many years, including problems with permanent teeth. Due to a number of factors such as fear of dentists, problems treating very young patients, lack of access to dental care and cost of dental care, many young children do not have access to adequate oral health procedures. Prevention of oral health issues at an early age can be done through the use of adequate brushing and flossing on a timely basis. Maybe if children could have a more intimate view of their teeth apart from just looking at it in the mirror, they may have a greater interest in keeping their teeth healthy.

### 2. Design 
The project will involve taking multiple images of the participants teeth, using a night vision camera attached to a Raspberry Pi. Images will be taken at as many angles as possible to form a composite image of all teeth in the mouth. The composite image will be portrayed on a wall at a very enlarged scale. The child can open the mouth image and walk inside their mouth and squat down to see a much closer and detailed view of their teeth. Turning around will allow them to see the inside parts of their teeth that they don’t normally see. They can also see areas with visible decay. Information can be provided on various aspects of the teeth and oral hygiene. The information provided will be dependent on hand gestures/controller buttons. Having a personal upfront view of their teeth (instead of a generic mouth) might encourage them to take better care of their teeth.

### 3.Devices:
- Raspberry Pi 4 with night vision camera that will capture images of the mouth/teeth.
- Images will be sent to Windows machine
- 360 Imaging software that will stitch the mouth/teeth images together
- Unity Software that will build the virtual environment
- Oculus Quest for interacting with the environment

### 3. Virtual Reality Environment.
The composite image will get larger as the user walks towards a certain point. At a certain threshold, the user can use hand gestures/controller buttons to open the mouth and step inside. Squatting will provide a closer view of the inside of the lower teeth, while standing will result in seeing the inside of the upper teeth. Stepping away past a certain threshold will put the user outside the mouth. There will be icons which the user can click on, that will provide information about the tooth or oral hygiene.

### 4. Virtual Reality Environment.
The composite image will get larger as the user walks towards a certain point. At a certain threshold, the user can use hand gestures/controller buttons to open the mouth and step inside. Squatting will provide a closer view of the inside of the lower teeth, while standing will result in seeing the inside of the upper teeth. Stepping away past a certain threshold will put the user outside the mouth. There will be icons which the user can click on, that will provide information about the tooth or oral hygiene.

### 5. Major work to be done include:
- Stitching all images together that can create a composite image of the inside and outside of the tooth/mouth
- Setting boundaries/threshold to view/step into inside or outside of mouth
- Enlarging image based on movement/gestures
- Using image recognition to place icons to provide information. Since each mouth is different, the icons have to be placed dynamically

### 6. References:
[1] Milgrom, P., Zero, D. T.,DDS, Tanzer, J. M. (2009). An Examination of the Advances in Science and Technology of Prevention of Tooth Decay in Young Children Since the Surgeon General's Report on Oral Health. Academic Pediatrics, 9(6), 404-409

[2] Gibson‐Moore, H.,  Benelam, B., (2018). Young children and snacks – is tooth brushing alone not enough to prevent tooth decay? Nutrition Bulletin 43(3), 248-254
