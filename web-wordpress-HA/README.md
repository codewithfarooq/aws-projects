Steps:
	
	Network setup
		Configure the VPC (module1.yaml)

	Build the Data Tier
		Set up RDS Database (module2.yaml)
		Set up Elasticache for Memcached (module3.yaml)
		Create a shared file system (module4.yaml)

	Build the application Tier:
		Create the Load Balancer (module5.yaml)
		Create the Launch Configuration (module6.yaml)
		Create the App server (module7.yaml)

	Speed up the website:
		Configure Caching
		Add a content Delivery Network (module9.yaml)