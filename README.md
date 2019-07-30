# Setup

1. Make sure to work inside of a Python 3 Virtual Environment
2. Install requirements with `pip install -r requirements.txt`
3. Copy the contents of `.env-sample` to `.env` and then put in your Frame.io token
4. Modify `example.py` with the correct `asset_parent_id`
5. Run `python example.py` and watch it upload!


## Notes

I recently started running into issues with the `mimetypes` library and `utf-8` decoding. Not sure what's up with that
