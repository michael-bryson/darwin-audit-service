#
# Copyright 2022 Micro Focus or one of its affiliates.
#
# The only warranties for products and services of Micro Focus and its
# affiliates and licensors ("Micro Focus") are set forth in the express
# warranty statements accompanying such products and services. Nothing
# herein should be construed as constituting an additional warranty.
# Micro Focus shall not be liable for technical or editorial errors or
# omissions contained herein. The information contained herein is subject
# to change without notice.
#
# Contains Confidential Information. Except as specifically indicated
# otherwise, a valid license is required for possession, use or copying.
# Consistent with FAR 12.211 and 12.212, Commercial Computer Software,
# Computer Software Documentation, and Technical Data for Commercial
# Items are licensed to the U.S. Government under vendor's standard
# commercial license.
#

ARG DOCKER_HUB_PUBLIC=docker.io

FROM ${DOCKER_HUB_PUBLIC}/cafaudit/audit-service:3

    # Common environment variables
ENV CAF_ELASTIC_PROTOCOL="http" \
    CAF_AUDIT_MODE="elasticsearch" \
    CAF_ELASTIC_HOST_VALUES="elasticsearch" \
    CAF_ELASTIC_PORT_VALUE="9200" \
    CAF_ELASTIC_NUMBER_OF_SHARDS="5" \
    CAF_ELASTIC_NUMBER_OF_REPLICAS="1"
