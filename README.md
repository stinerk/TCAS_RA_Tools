# TCAS_RA_Tools
모든 파일은 Jupyter Notebook에서 활용할 수 있도록 작성되었습니다.
2 Flights_Trajectories_uplpoad.ibynb 파일은 2개의 항적을 불러와서 시현하는 코드입니다.
위 코드를 사용하기 위해서는 Traffic 라이브러리를 활용해서 가상환경을 구성해야 합니다. 자세한 것은 Xoolive/Traffic 을 참고하시기 바랍니다.
get_state_vectors_from_TCAS_RA_time.ibynb 파일은 미리 확인한 TID가 없는 경우 TCAS RA가 작동한 항공기의 작동 시간 및 좌표를 기준으로 근처의 항적을 찾아서 CSV 파일로 저장하는 코드입니다.
위 코드를 사용하기 위해서는 PyopenSky 라이브러리와 PymodeS 라이브러리가 필요합니다. 
