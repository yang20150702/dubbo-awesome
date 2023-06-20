# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.223 ops/ms
# Warmup Iteration   2: 8.916 ops/ms
# Warmup Iteration   3: 9.959 ops/ms
Iteration   1: 10.513 ops/ms
Iteration   2: 10.598 ops/ms
Iteration   3: 10.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.631 ±(99.9%) 2.491 ops/ms [Average]
  (min, avg, max) = (10.513, 10.631, 10.781), stdev = 0.137
  CI (99.9%): [8.140, 13.121] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.650 ops/ms
# Warmup Iteration   2: 10.679 ops/ms
# Warmup Iteration   3: 10.864 ops/ms
Iteration   1: 11.175 ops/ms
Iteration   2: 11.075 ops/ms
Iteration   3: 11.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.136 ±(99.9%) 0.978 ops/ms [Average]
  (min, avg, max) = (11.075, 11.136, 11.175), stdev = 0.054
  CI (99.9%): [10.158, 12.114] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.473 ops/ms
# Warmup Iteration   2: 10.281 ops/ms
# Warmup Iteration   3: 10.582 ops/ms
Iteration   1: 10.550 ops/ms
Iteration   2: 10.463 ops/ms
Iteration   3: 10.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.548 ±(99.9%) 1.509 ops/ms [Average]
  (min, avg, max) = (10.463, 10.548, 10.629), stdev = 0.083
  CI (99.9%): [9.038, 12.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.869 ops/ms
# Warmup Iteration   2: 7.867 ops/ms
# Warmup Iteration   3: 8.019 ops/ms
Iteration   1: 7.957 ops/ms
Iteration   2: 8.159 ops/ms
Iteration   3: 8.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.055 ±(99.9%) 1.849 ops/ms [Average]
  (min, avg, max) = (7.957, 8.055, 8.159), stdev = 0.101
  CI (99.9%): [6.206, 9.904] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.192 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.007 ms/op
Iteration   1: 3.083 ±(99.9%) 0.002 ms/op
Iteration   2: 3.044 ±(99.9%) 0.003 ms/op
Iteration   3: 3.028 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.052 ±(99.9%) 0.517 ms/op [Average]
  (min, avg, max) = (3.028, 3.052, 3.083), stdev = 0.028
  CI (99.9%): [2.535, 3.568] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.798 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.801 ±(99.9%) 0.004 ms/op
Iteration   1: 2.897 ±(99.9%) 0.004 ms/op
Iteration   2: 2.882 ±(99.9%) 0.003 ms/op
Iteration   3: 2.928 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.902 ±(99.9%) 0.437 ms/op [Average]
  (min, avg, max) = (2.882, 2.902, 2.928), stdev = 0.024
  CI (99.9%): [2.465, 3.339] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.754 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.003 ms/op
Iteration   1: 3.066 ±(99.9%) 0.006 ms/op
Iteration   2: 3.034 ±(99.9%) 0.002 ms/op
Iteration   3: 3.042 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.047 ±(99.9%) 0.303 ms/op [Average]
  (min, avg, max) = (3.034, 3.047, 3.066), stdev = 0.017
  CI (99.9%): [2.745, 3.350] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.222 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.011 ms/op
Iteration   1: 3.930 ±(99.9%) 0.005 ms/op
Iteration   2: 3.985 ±(99.9%) 0.034 ms/op
Iteration   3: 3.996 ±(99.9%) 0.052 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.970 ±(99.9%) 0.638 ms/op [Average]
  (min, avg, max) = (3.930, 3.970, 3.996), stdev = 0.035
  CI (99.9%): [3.333, 4.608] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.220 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  6.595 ms/op
                 createUser·p0.9999: 17.607 ms/op
                 createUser·p1.00:   17.891 ms/op

Iteration   2: 3.017 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.400 ms/op
                 createUser·p0.95:   3.629 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  8.651 ms/op
                 createUser·p0.9999: 23.069 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   3: 3.032 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.624 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.792 ms/op
                 createUser·p0.999:  10.381 ms/op
                 createUser·p0.9999: 16.088 ms/op
                 createUser·p1.00:   16.384 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318257
  mean =      3.016 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21115 
    [ 2.500,  5.000) = 295408 
    [ 5.000,  7.500) = 1362 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.624 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     22.459 ms/op
     p(99.9990) =     23.444 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.791 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  5.777 ms/op
                 existUser·p0.9999: 18.102 ms/op
                 existUser·p1.00:   18.743 ms/op

Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  6.702 ms/op
                 existUser·p0.9999: 22.890 ms/op
                 existUser·p1.00:   23.593 ms/op

Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  10.787 ms/op
                 existUser·p0.9999: 23.679 ms/op
                 existUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321804
  mean =      2.981 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34552 
    [ 2.500,  5.000) = 286107 
    [ 5.000,  7.500) = 846 
    [ 7.500, 10.000) = 75 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.135 ms/op
     p(99.9900) =     23.167 ms/op
     p(99.9990) =     23.848 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.224 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.021 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.137 ms/op
                 getUser·p0.999:  6.496 ms/op
                 getUser·p0.9999: 12.491 ms/op
                 getUser·p1.00:   12.714 ms/op

Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.719 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  8.133 ms/op
                 getUser·p0.9999: 18.822 ms/op
                 getUser·p1.00:   19.300 ms/op

Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.647 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  6.259 ms/op
                 getUser·p0.9999: 14.752 ms/op
                 getUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316974
  mean =      3.030 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1149 
    [ 1.250,  2.500) = 19808 
    [ 2.500,  3.750) = 280035 
    [ 3.750,  5.000) = 14902 
    [ 5.000,  6.250) = 618 
    [ 6.250,  7.500) = 180 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.021 ms/op
     p(99.9900) =     17.800 ms/op
     p(99.9990) =     19.191 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.074 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.024 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.010 ms/op
Iteration   1: 3.920 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  12.473 ms/op
                 listUser·p0.9999: 14.884 ms/op
                 listUser·p1.00:   15.876 ms/op

Iteration   2: 4.011 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  13.590 ms/op
                 listUser·p0.9999: 21.791 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   3: 3.996 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.867 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.795 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  19.262 ms/op
                 listUser·p0.9999: 25.657 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241430
  mean =      3.975 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3728 
    [ 2.500,  5.000) = 214684 
    [ 5.000,  7.500) = 21613 
    [ 7.500, 10.000) = 828 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 195 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     13.837 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.631 ± 2.491  ops/ms
ClientGrpc.existUser                       thrpt       3  11.136 ± 0.978  ops/ms
ClientGrpc.getUser                         thrpt       3  10.548 ± 1.509  ops/ms
ClientGrpc.listUser                        thrpt       3   8.055 ± 1.849  ops/ms
ClientGrpc.createUser                       avgt       3   3.052 ± 0.517   ms/op
ClientGrpc.existUser                        avgt       3   2.902 ± 0.437   ms/op
ClientGrpc.getUser                          avgt       3   3.047 ± 0.303   ms/op
ClientGrpc.listUser                         avgt       3   3.970 ± 0.638   ms/op
ClientGrpc.createUser                     sample  318257   3.016 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.624           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.498           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.651           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.459           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.593           ms/op
ClientGrpc.existUser                      sample  321804   2.981 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.605           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.135           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.167           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.362           ms/op
ClientGrpc.getUser                        sample  316974   3.030 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.647           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.021           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.800           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.300           ms/op
ClientGrpc.listUser                       sample  241430   3.975 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.867           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.837           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.281           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.706           ms/op
