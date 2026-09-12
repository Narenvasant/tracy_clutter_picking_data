# Tracy clutter picking: recorded attempts

Recorded pick attempts of the `tracy_clutter_picking` experiment in
[cognitive_robot_abstract_machine](https://github.com/cram2/cognitive_robot_abstract_machine)
(`experiments/src/experiments/causal_reasoning/tracy_clutter_picking`). The data is
kept here so the code repository does not carry it.

`milk_clutter_attempts.json` holds 300 attempts of Tracy's left arm picking one milk
carton out of a clutter of ten in MuJoCo, held by contact friction alone, recorded with
the experiment's `collect_data` module. Each attempt is one `ClutterPickScene` in the
JSON layout `krrood.adapters.json_serializer` writes.

The experiment fetches this file into the user's cache on first use; a tag pins the
version it reads.
