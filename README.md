# streamlit_get_protocol

Get window.location.protocol

## Installation:
```
pip install streamlit_get_protocol
```
## Example:
```
import streamlit as st  
from streamlit_get_protocol import get_protocol

protocol = get_protocol()

if protocol:  
    st.write(protocol)
```    
