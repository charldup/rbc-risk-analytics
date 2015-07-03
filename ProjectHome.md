## OVERVIEW ##
This is where we work on the development of **Risk-Based Capital** analytics that measure the risk of insurance companies not being able to pay their claims.  Most of the modules have already been created, but a lot of work remains.  Potential collaborators and contributors are encouraged to take part in this project.

A companion website, http://www.Risk-BasedCapital.org, contains important additional materials and a discussion forum.  We suggest that you visit that website as it is part of the same project.  There you can express your views and see the opinions and suggestions that have been posted by others.

## WHAT IT IS AND WHAT IT ISN'T ##
While many of the materials posted here have been presented to the P/C Risk-Based Capital Committee of the American Academy of Actuaries, they are not endorsed or approved by the Committee or the Academy.  They represent ongoing research and in their current form are not a finished work product.  Any materials on this site are provided on an "as is" basis, without warranties or conditions of any kind, either express or implied, including, without limitation, any warranties or conditions of title, non-infringement, merchantability, or fitness for a particular purpose. You are solely responsible for determining the appropriateness of using or redistributing these materials and assume any associated risks.

Alex Krutov, Ernesto Schirmacher and Sholom Feldblum explicitly disclaim all liability for any consequences resulting from the use of the materials posted on this site and the linked http://www.Risk-BasedCapital.org site.  Alex Krutov and Sholom Feldblum, in whatever role each of them may play in the operation of this site or the linked site, are not acting in their respective capacities as the chair and member of the P/C Risk-Based Capital Committee of the American Academy of Actuaries.  The content of this site and the linked site are not sponsored by or considered a work product of the American Academy of Actuaries, the Casualty Actuarial Society, the Society of Actuaries, the NAIC, any other organizations or individuals, or past or current employers of Sholom Feldblum, Ernesto Schirmacher, Alex Krutov or any of the administrators or moderators of these sites.


## PROJECT GOALS ##
### Main ###
The main purpose of this open-source project is to create standard software for assessing Risk-Based Capital in ways that
  1. incorporate the modern actuarial and risk science approaches that are already utilized in internal modeling of insurance enterprises,
  1. provide an opportunity for a broad community to scrutinize the overall approach and identify any potential weaknesses that need to be addressed,
  1. take advantage of the open-source model to utilize input from any interested parties and to create a better software product,
  1. overcome the black-box perception by allowing anybody to audit the software and to use it in ways that will clearly show the main drivers of the final results,
  1. provide a service to the actuarial, risk analysis, and regulatory communities by developing an open-source product for the calculation of Risk-Based Capital.

In the software implementation, we are trying to preserve the flexibility of allowing the users to choose among the various methods and risk metrics.  For example, in the context of the standard formula for calculating minimum solvency requirements for insurance companies, regulators should have the ability to choose the risk measure they consider appropriate and the level of this risk measure to calibrate Risk-Based Capital.  The final product will have the ability to provide regulators with these choices in establishing standard solvency capital requirements.

We also want to stimulate the discussion and research of risk in insurance solvency regulation, internal capital modeling, and broader contexts.


### Secondary ###
The secondary purpose is to stimulate the development of risk analytics using the open-source model.  While this purpose is important, it is not our current focus.

## SOFTWARE FILES CURRENTLY POSTED ##
Most modules are presented in the form of very large Microsoft Excel workbooks that can run simulations.  This highly inefficient format is important at the current stage because it allows anybody to review, with relative ease, the logic of the calculations and the overall structure of the models.