---
---
# Telema EDI Setup

## How to set up a connection with Telema server
Open  **Telema EDI Setup** and the FastTab  **Connection.**  
Please ask the following information from Telema to fill in here:

Field: |
- |
**API URL** |
**API Channel Id** |
**API Key** |

After filling  **Connection** FastTab use function  **Test Connection** to ensure that connection with Telema has been established.

## Business-to-business document exchange in BC
To send documents, open **Telema EDI Setup** and activate the check box **Publish E-Document Web Service** - this allows document exchange between Business Central companies.
Then open the **Customer Card** from **Customers** list and on the Telema EDI fast tab select **Sending to Channel** *BC E-Document Web Service*.
Please ask the company to whom you want to send documents through BC for the following information:

Field:
- |
**E-Document Web Service URL** |
**E-Document Web Service User** |
**E-Document Web Service Key** |

To receive documents, you must provide the sender with the following information: web service URL, user name and password.
To do this, open **Web Services** and select **SOAP URL** from the **TED E-Document Web Service** line. This is the **E-Document Web Service URL**.
Then open **Users** and create a user for the sending company. Specify **User Name** and **Web Service Access Key**. Under **Actions**, you can specify what will be the **Key Expiration Date** or set it to **Key Never Expires**.



## How to receive and send e-documents

See the manual for:  
[Inbound E-Documents](inbound-edocuments)  
[Outbound E-Documents](outbound-edocuments)
