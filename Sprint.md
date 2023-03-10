---
title: Sprint
---
title: Sprint 11 for (V1.64.2.6)


date: 7.2.2023


product_name: TestFW V2.0


git_branch: master


git_revision: 1.64.2.6_23.777


versions:

    Pro: V1.64.2.6
    Eco: V1.64.2.6
    Firmware: V1.64.2.6

packages:

    packages:
        - https://11.test.com/svn/releases/V2.0/V2.0_Release/Sprint%11/Pro_1.64.2.6_23.777.seco
        - https://11.test.com/svn/releases/V2.0/V2.0_Release/Sprint%11/Eco_1.64.2.6_23.777.seco

tickets:

    Official:
        New Functions:
            - 'FW-1234: SP16 patch4 hotfix1'
            - 'FW-1111: integrate Codesys sp16 patch4 hotfix'
        Closed Bugs:
            - 'FW-7878: Block DataLogManager'
            - 'FW-9493: Library IoTDriver'
        Restrictions:
            - Pro controller doesn't boot with connected USB key
    Company Internal:
        New Functions:
            - 'FW-9442: VxWorks 7'
        Closed Bugs:
            - 'FW-9514: Library MotionInterface'
            - 'FW-9394: Controllers stuck in boot state forever'
        Refactoring:
            - 'FW-9313: Update default UR configuration and objects'
    Team Internal:
        New Functions:
            - 'FW-9982: At application download load netX firmware'
        Closed Bugs:
            - 'FW-9476: Remove compiler warning'
        Refactoring:
            - 'FW-9913: Update default US objects'

---