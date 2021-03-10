# NDC-list
A comprehensive NDC list disclaimer for medical software

An asterisk may appear in either a product code or a package code. It acts as a placeholder and indicates the
configuration of the NDC. Thus, there is either a 5-4-1 or a 5-3-2 configuration for the three segments of the
NDC. Because of a conflict with the HIPAA standard of an 11-digit NDC, many programs will pad the product
code or package code segments of the NDC with a leading zero instead of the asterisk.
Since a zero can be a valid digit in the NDC, this can lead to confusion when trying to reconstitute the NDC back
to its FDA standard. For example, 12345-0678-09 (11 digits) could be 12345-678-09 or 12345-0678-9
depending on the firm's configuration. By storing the segments as character data and using the asterisk as
placeholders, there is no confusion. In the example, the FDA stores the segments as 12345-*678-09 for a 5-3-2
configuration or 12345-0678-*9 for a 5-4-1 configuration. Therefore, the 11-digit NDC numbers for the Infanrix
are
● 58160-0810-11 (10 pack single-dose vials)
● 58160-0810-52 (10 pack single-dose T-L syringes)
