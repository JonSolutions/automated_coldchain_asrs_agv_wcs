# Automated_Coldchain_Asrs_Agv_Wcs_Fullstack_Repo

Production service architecture and telemetry verification suite.

## Modules
- `deployment/opcua_edge/automated_ColdChai_calibration_registry.json` (315 lines)
- `deployment/opcua_edge/automated_ColdChai_k8s_workloads.yaml` (295 lines)
- `deployment/opcua_edge/automated_ColdChai_openapi_contract.yaml` (839 lines)
- `deployment/opcua_edge/automated_ColdChai_prometheus_alerts.yaml` (315 lines)
- `warehouse_db/migrations/V001__automated_ColdChai_initial_core_topology.sql` (1606 lines)
- `warehouse_db/migrations/V002__automated_ColdChai_partitioned_timeseries_store.sql` (1606 lines)
- `warehouse_db/migrations/V003__automated_ColdChai_invariant_trigger_procedures.sql` (1606 lines)
- `warehouse_db/migrations/V004__automated_ColdChai_materialized_kpi_rollups.sql` (1606 lines)
- `warehouse_db/migrations/V005__automated_ColdChai_calibrated_baseline_seed.sql` (1606 lines)
- `wcs_actors/elixir_supervisor/arrhenius_fefo_pallet_state_estimator_core.ex` (886 lines)
- `wcs_actors/elixir_supervisor/cbs_mapf_agv_grid_ring_buffer_dispatcher.ex` (886 lines)
- `wcs_actors/elixir_supervisor/conveyor_divert_sorter_telemetry_mux_bridge.ex` (886 lines)

## Running Tests
```bash
pytest -v
python -m unittest discover -s tests
```
