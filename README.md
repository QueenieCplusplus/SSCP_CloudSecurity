# SSCP CloudSecurity

 BaaS, Backend as a Service
 
 Cloud tech is the storage tech that level up according to requirements to meet on:
 
 * SLO, Service Level Objective
 
 * SLA, Service Level Agreement
 
    * Cost
    
    * Availability
    
    * Capacity
    
    * Functionality
    
    * Performance
 
 # Data Storage & Transmission
 
 All the core of all cloud services are software tools with 3 functions:
 
 - [x] Server side to process data || run app
 
 - [x] Network for transmiss data
 
 - [x] Storage to preserve data
 
 Cloud Storage is defined as a data storage that is made available as a Service via Network. Its related product includes to build a block of "Physical Storage System, 雲端存儲系統" (HDDs || SDDs).
 
 * SDDs, Solid State Drive
 
    Fast & Flexible
 
 * HDDs, Hard Disk Drive
 
    High Capacity
    
# Clouds Infra

* vVolume Storage, 虛擬硬碟：

                  VM     VM     VM      VM     VM ...
                               |

                          Hypervisors

                               |
                               |

                               HD
                         Clients Server
                            
                               |
                               |
                   
                   “Volume Storage Controller”
                   
        a vitual hard disk drive (phisical array) that can be attached to VM instance  to be used to host data with a file system.

               volume      volume     volume ...

                               |
                               |
 
                       vStorage Controller
            
                               |
                               |
                               
                      Physical Storage Pool

* Objective Storage, 目標（物件）存儲：


                               HD
                         Clients Server
                            
                               |
                               |
                   
                   “Objective Storage Controller” 
                   
              File Share Access Via API or Web Interface

               volume      volume     volume ...

                               |
                               |
 
                       vStorage Controller
            
                               |
                               |
                               
                      Physical Storage Pool


