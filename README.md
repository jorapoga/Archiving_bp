# Archiving_bp
ABAP Archiving BP: 

Actually does not exist an SAP Standard function module or BAPI to archive Business Partner and the support manner is using BUPA_PRE_DA and SARA transaction. The Archive Objets let us “to impact” the relational model corresponding to the type of specific BP (Generic, Customer, or Vendor).

An approach to archive BPs was presented using a custom function module within S/4HANA 1909 version that has call transactions to BUPA_PRE_DA and SARA. It is completely functional to archive BP generics and BP Customers. Also is easily enhanced to archive BP Vendors.
