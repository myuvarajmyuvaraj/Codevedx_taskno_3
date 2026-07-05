# Codevedx_taskno_3
Data Analytics with python 
# Display a summary
	print("=" * 55)
	print("         DATASET SUMMARY")
	print("=" * 55)
	print(f"\n📊 Sales Data       : {sales_data.shape[0]} rows × "f"{sales_data.shape[1]} columns")
	print(f"📊 Satisfaction Data: {satisfaction_data.shape[0]} rows × " f"{satisfaction_data.shape[1]} columns")
	print(f"📊 Customer Data    : {customer_data.shape[0]} rows × "f"{customer_data.shape[1]} columns")
	print(f"📊 Store Performance: {store_performance.shape[0]} rows × "f"{store_performance.shape[1]} columns")

	print("\n--- Sales Data Preview ---")
	print(sales_data.head(3).to_string(index=False))

	print("\n--- Customer Data Preview ---")
	print(customer_data.head(3).to_string(index=False))
