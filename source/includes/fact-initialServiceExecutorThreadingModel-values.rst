.. list-table::
   :header-rows: 1
   :widths: 20 40
   
   * - Value
     - Description

   * - ``dedicated``
     - Each client is assigned a new thread that lasts until the 
       connection is closed.

   * - ``borrowed``
     - Each client uses a thread from a pool of threads. Each new 
       operation may use a different thread.