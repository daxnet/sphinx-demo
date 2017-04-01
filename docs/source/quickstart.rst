Quick Start
===========
Following is the example of a C# code:

.. code-block:: c#
   :linenos:
   :emphasize-lines: 3,5

   public class Account : IAggregateRoot<int>
   {
    public virtual int Id { get; set; }
    
    public virtual string Name { get; set; }
    
    public virtual string Email { get; set; }
    
    public virtual List<AccountProperty> Properties { get; set; }
    
    public Account()
    {
     this.Properties = new List<AccountProperty>();
    }
   }

Above code simply shows the model of an Account object.

Following is the code read from an external file:

.. literalinclude:: code/example.cpp
   :language: c++
   :emphasize-lines: 2,3,4
   :linenos:
   :encoding: latin-1
