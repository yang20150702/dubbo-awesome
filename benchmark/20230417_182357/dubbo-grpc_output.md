# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.114 ops/ms
# Warmup Iteration   2: 8.845 ops/ms
# Warmup Iteration   3: 10.141 ops/ms
Iteration   1: 10.636 ops/ms
Iteration   2: 10.480 ops/ms
Iteration   3: 10.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.515 ±(99.9%) 1.970 ops/ms [Average]
  (min, avg, max) = (10.429, 10.515, 10.636), stdev = 0.108
  CI (99.9%): [8.545, 12.484] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 6.975 ops/ms
# Warmup Iteration   2: 10.322 ops/ms
# Warmup Iteration   3: 11.049 ops/ms
Iteration   1: 11.203 ops/ms
Iteration   2: 11.072 ops/ms
Iteration   3: 11.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.112 ±(99.9%) 1.428 ops/ms [Average]
  (min, avg, max) = (11.063, 11.112, 11.203), stdev = 0.078
  CI (99.9%): [9.684, 12.541] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.735 ops/ms
# Warmup Iteration   2: 9.719 ops/ms
# Warmup Iteration   3: 10.084 ops/ms
Iteration   1: 10.259 ops/ms
Iteration   2: 10.483 ops/ms
Iteration   3: 10.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.365 ±(99.9%) 2.054 ops/ms [Average]
  (min, avg, max) = (10.259, 10.365, 10.483), stdev = 0.113
  CI (99.9%): [8.311, 12.419] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.463 ops/ms
# Warmup Iteration   2: 7.541 ops/ms
# Warmup Iteration   3: 7.982 ops/ms
Iteration   1: 8.035 ops/ms
Iteration   2: 8.195 ops/ms
Iteration   3: 8.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.144 ±(99.9%) 1.722 ops/ms [Average]
  (min, avg, max) = (8.035, 8.144, 8.202), stdev = 0.094
  CI (99.9%): [6.422, 9.866] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.193 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.004 ms/op
Iteration   1: 3.055 ±(99.9%) 0.005 ms/op
Iteration   2: 3.033 ±(99.9%) 0.002 ms/op
Iteration   3: 2.992 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.027 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (2.992, 3.027, 3.055), stdev = 0.032
  CI (99.9%): [2.447, 3.606] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.071 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.967 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.923 ±(99.9%) 0.004 ms/op
Iteration   1: 2.911 ±(99.9%) 0.002 ms/op
Iteration   2: 2.952 ±(99.9%) 0.003 ms/op
Iteration   3: 2.900 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.921 ±(99.9%) 0.496 ms/op [Average]
  (min, avg, max) = (2.900, 2.921, 2.952), stdev = 0.027
  CI (99.9%): [2.426, 3.417] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.235 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 3.046 ±(99.9%) 0.004 ms/op
Iteration   2: 2.992 ±(99.9%) 0.004 ms/op
Iteration   3: 3.020 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.019 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (2.992, 3.019, 3.046), stdev = 0.027
  CI (99.9%): [2.531, 3.507] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.002 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.024 ms/op
Iteration   1: 3.948 ±(99.9%) 0.024 ms/op
Iteration   2: 3.940 ±(99.9%) 0.013 ms/op
Iteration   3: 3.844 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.911 ±(99.9%) 1.052 ms/op [Average]
  (min, avg, max) = (3.844, 3.911, 3.948), stdev = 0.058
  CI (99.9%): [2.859, 4.963] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.266 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
Iteration   1: 3.138 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.915 ms/op
                 createUser·p0.999:  8.880 ms/op
                 createUser·p0.9999: 19.032 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  9.886 ms/op
                 createUser·p0.9999: 14.464 ms/op
                 createUser·p1.00:   14.778 ms/op

Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.592 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  13.631 ms/op
                 createUser·p0.9999: 16.138 ms/op
                 createUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309639
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 482 
    [ 1.250,  2.500) = 19756 
    [ 2.500,  3.750) = 267165 
    [ 3.750,  5.000) = 19877 
    [ 5.000,  6.250) = 1284 
    [ 6.250,  7.500) = 513 
    [ 7.500,  8.750) = 196 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     18.514 ms/op
     p(99.9990) =     19.330 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.003 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
Iteration   1: 2.959 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  6.537 ms/op
                 existUser·p0.9999: 12.445 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   2: 2.920 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  5.997 ms/op
                 existUser·p0.9999: 13.894 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   3: 2.936 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.899 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  9.407 ms/op
                 existUser·p0.9999: 16.883 ms/op
                 existUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326584
  mean =      2.938 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 875 
    [ 1.250,  2.500) = 38010 
    [ 2.500,  3.750) = 278015 
    [ 3.750,  5.000) = 8516 
    [ 5.000,  6.250) = 731 
    [ 6.250,  7.500) = 180 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.600 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.754 ms/op
     p(99.9900) =     16.171 ms/op
     p(99.9990) =     17.317 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.245 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
Iteration   1: 3.054 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  6.893 ms/op
                 getUser·p0.9999: 14.205 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   2: 2.997 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.393 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  6.777 ms/op
                 getUser·p0.9999: 14.598 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   3: 3.040 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.431 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.939 ms/op
                 getUser·p0.9999: 16.055 ms/op
                 getUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316609
  mean =      3.030 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 448 
    [ 1.250,  2.500) = 20190 
    [ 2.500,  3.750) = 281592 
    [ 3.750,  5.000) = 12812 
    [ 5.000,  6.250) = 1059 
    [ 6.250,  7.500) = 262 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 106 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.393 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      6.847 ms/op
     p(99.9900) =     14.909 ms/op
     p(99.9990) =     16.414 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.191 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.009 ms/op
Iteration   1: 3.946 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.287 ms/op
                 listUser·p0.9999: 14.875 ms/op
                 listUser·p1.00:   16.237 ms/op

Iteration   2: 3.974 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  14.277 ms/op
                 listUser·p0.9999: 17.755 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 3.874 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  15.325 ms/op
                 listUser·p0.9999: 20.199 ms/op
                 listUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244203
  mean =      3.931 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3262 
    [ 2.500,  5.000) = 218463 
    [ 5.000,  7.500) = 21392 
    [ 7.500, 10.000) = 658 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     13.877 ms/op
     p(99.9900) =     18.271 ms/op
     p(99.9990) =     20.531 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.515 ± 1.970  ops/ms
ClientGrpc.existUser                       thrpt       3  11.112 ± 1.428  ops/ms
ClientGrpc.getUser                         thrpt       3  10.365 ± 2.054  ops/ms
ClientGrpc.listUser                        thrpt       3   8.144 ± 1.722  ops/ms
ClientGrpc.createUser                       avgt       3   3.027 ± 0.580   ms/op
ClientGrpc.existUser                        avgt       3   2.921 ± 0.496   ms/op
ClientGrpc.getUser                          avgt       3   3.019 ± 0.488   ms/op
ClientGrpc.listUser                         avgt       3   3.911 ± 1.052   ms/op
ClientGrpc.createUser                     sample  309639   3.101 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.592           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.776           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.568           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.514           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.464           ms/op
ClientGrpc.existUser                      sample  326584   2.938 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.757           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.754           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.171           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.465           ms/op
ClientGrpc.getUser                        sample  316609   3.030 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.393           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.847           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.909           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.777           ms/op
ClientGrpc.listUser                       sample  244203   3.931 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.866           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.877           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.271           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.611           ms/op
