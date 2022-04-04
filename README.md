# AirMouse
Using hand gestures as a mouse

Update date the mediapip solution_base.py at line 513 to 'return getattr(packet_creator, 'create_' + packet_data_type.value)(True if round(data)>0 else False)' if you encountered

TypeError: create intO: incompatible function arquments. The following arqument types are supported
1.(arg0:int)-> mediapipe.python._framework_bindings.packet.Packet
