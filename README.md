# Information on scripts-expleo Repo
--Contains scripts as a part of expleo technical assessment---

1. Attached are the zip files for business scenarios BP01 - Paysystem and BP02 - Create Ad respectively.

2. Scripts are created in HP Loadrunner v12.60, I recommend to use latest version of Loadrunner to replay the scripts however they are prepared in web protocol hence  it should be easily executed in lower versions of HP Loadrunner as well.

3. To run the scripts, simple extract the respective Zip files and open BP01_PaySystems.usr file for BP01 scenario and BP02_Create_Ad.usr file for BP02 scenario in loadrunner latest version (if available) and click on Run button.

4. In scripts, Business transactions are started with lr_start_transaction and ends with lr_end_transaction

5. Transactions are made PASS/FAIL based on if else logic and possible text checkpoints extracted from responses for verification purpose.

