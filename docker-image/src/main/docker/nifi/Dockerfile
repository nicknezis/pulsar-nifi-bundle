#
# Licensed to the Apache Software Foundation (ASF) under one or more
# contributor license agreements.  See the NOTICE file distributed with
# this work for additional information regarding copyright ownership.
# The ASF licenses this file to You under the Apache License, Version 2.0
# (the "License"); you may not use this file except in compliance with
# the License.  You may obtain a copy of the License at
#
#      http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.
#

FROM apache/nifi:1.15.3


#############################################################################
# Add the custom NAR files
#############################################################################

COPY --chown=nifi:nifi maven/modules/maven-assembly-plugin/nifi-pulsar-*.nar /opt/nifi/nifi-current/lib/

#############################################################################
# Add resource files for testing
#############################################################################
COPY --chown=nifi:nifi resources /resources
