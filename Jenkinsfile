from typing import Optional, List


class Exclude:
    ruby_version: float
    database: Optional[str]

    def __init__(self, ruby_version: float, database: Optional[str]) -> None:
        self.ruby_version = ruby_version
        self.database = database


class Welcome10:
    ruby_version: List[float]
    exclude: List[Exclude]

    def __init__(self, ruby_version: List[float], exclude: List[Exclude]) -> None:
        self.ruby_version = ruby_version
        self.exclude = exclude
