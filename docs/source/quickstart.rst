Quick Start
===========
Following is the example of a C# code:

.. code-block:: c#

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


