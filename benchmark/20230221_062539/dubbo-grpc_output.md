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
# Warmup Iteration   1: 4.488 ops/ms
# Warmup Iteration   2: 9.180 ops/ms
# Warmup Iteration   3: 9.956 ops/ms
Iteration   1: 10.326 ops/ms
Iteration   2: 10.001 ops/ms
Iteration   3: 10.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.121 ±(99.9%) 3.254 ops/ms [Average]
  (min, avg, max) = (10.001, 10.121, 10.326), stdev = 0.178
  CI (99.9%): [6.867, 13.375] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.851 ops/ms
# Warmup Iteration   2: 10.615 ops/ms
# Warmup Iteration   3: 10.460 ops/ms
Iteration   1: 10.657 ops/ms
Iteration   2: 10.575 ops/ms
Iteration   3: 10.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.613 ±(99.9%) 0.750 ops/ms [Average]
  (min, avg, max) = (10.575, 10.613, 10.657), stdev = 0.041
  CI (99.9%): [9.862, 11.363] (assumes normal distribution)


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
# Warmup Iteration   1: 6.759 ops/ms
# Warmup Iteration   2: 10.008 ops/ms
# Warmup Iteration   3: 10.082 ops/ms
Iteration   1: 10.164 ops/ms
Iteration   2: 10.283 ops/ms
Iteration   3: 10.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.248 ±(99.9%) 1.322 ops/ms [Average]
  (min, avg, max) = (10.164, 10.248, 10.295), stdev = 0.072
  CI (99.9%): [8.926, 11.569] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.193 ops/ms
# Warmup Iteration   2: 7.705 ops/ms
# Warmup Iteration   3: 7.736 ops/ms
Iteration   1: 7.854 ops/ms
Iteration   2: 7.916 ops/ms
Iteration   3: 7.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.906 ±(99.9%) 0.874 ops/ms [Average]
  (min, avg, max) = (7.854, 7.906, 7.948), stdev = 0.048
  CI (99.9%): [7.032, 8.780] (assumes normal distribution)


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
# Warmup Iteration   1: 4.402 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.002 ms/op
Iteration   1: 3.106 ±(99.9%) 0.005 ms/op
Iteration   2: 3.122 ±(99.9%) 0.002 ms/op
Iteration   3: 3.252 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.160 ±(99.9%) 1.460 ms/op [Average]
  (min, avg, max) = (3.106, 3.160, 3.252), stdev = 0.080
  CI (99.9%): [1.700, 4.620] (assumes normal distribution)


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
# Warmup Iteration   1: 4.157 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.002 ms/op
Iteration   1: 3.016 ±(99.9%) 0.002 ms/op
Iteration   2: 3.018 ±(99.9%) 0.002 ms/op
Iteration   3: 3.049 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.028 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (3.016, 3.028, 3.049), stdev = 0.019
  CI (99.9%): [2.685, 3.370] (assumes normal distribution)


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
# Warmup Iteration   1: 4.279 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.006 ms/op
Iteration   1: 3.122 ±(99.9%) 0.004 ms/op
Iteration   2: 3.183 ±(99.9%) 0.002 ms/op
Iteration   3: 3.172 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.159 ±(99.9%) 0.595 ms/op [Average]
  (min, avg, max) = (3.122, 3.159, 3.183), stdev = 0.033
  CI (99.9%): [2.564, 3.754] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.603 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.073 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.010 ms/op
Iteration   1: 4.112 ±(99.9%) 0.010 ms/op
Iteration   2: 4.015 ±(99.9%) 0.010 ms/op
Iteration   3: 4.033 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.053 ±(99.9%) 0.941 ms/op [Average]
  (min, avg, max) = (4.015, 4.053, 4.112), stdev = 0.052
  CI (99.9%): [3.112, 4.994] (assumes normal distribution)


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.008 ms/op
Iteration   1: 3.190 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.617 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  6.688 ms/op
                 createUser·p0.9999: 17.300 ms/op
                 createUser·p1.00:   17.531 ms/op

Iteration   2: 3.250 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  7.546 ms/op
                 createUser·p0.9999: 19.245 ms/op
                 createUser·p1.00:   19.825 ms/op

Iteration   3: 3.253 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.171 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  8.968 ms/op
                 createUser·p0.9999: 21.851 ms/op
                 createUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 296922
  mean =      3.231 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19396 
    [ 2.500,  5.000) = 276110 
    [ 5.000,  7.500) = 1029 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.307 ms/op
     p(99.9900) =     20.694 ms/op
     p(99.9990) =     23.792 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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
# Warmup Iteration   1: 4.333 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.008 ms/op
Iteration   1: 3.035 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  6.138 ms/op
                 existUser·p0.9999: 16.277 ms/op
                 existUser·p1.00:   17.727 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.198 ms/op
                 existUser·p0.999:  6.909 ms/op
                 existUser·p0.9999: 18.299 ms/op
                 existUser·p1.00:   18.645 ms/op

Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.275 ms/op
                 existUser·p0.9999: 22.544 ms/op
                 existUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316948
  mean =      3.029 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36165 
    [ 2.500,  5.000) = 279917 
    [ 5.000,  7.500) = 672 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.521 ms/op
     p(99.9900) =     20.097 ms/op
     p(99.9990) =     22.703 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 4.507 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.006 ms/op
Iteration   1: 3.174 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.038 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  9.294 ms/op
                 getUser·p0.9999: 13.858 ms/op
                 getUser·p1.00:   14.139 ms/op

Iteration   2: 3.153 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.123 ms/op
                 getUser·p0.9999: 14.298 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   3: 3.103 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.045 ms/op
                 getUser·p0.9999: 18.874 ms/op
                 getUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305310
  mean =      3.143 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 224 
    [ 1.250,  2.500) = 19433 
    [ 2.500,  3.750) = 252407 
    [ 3.750,  5.000) = 32150 
    [ 5.000,  6.250) = 484 
    [ 6.250,  7.500) = 322 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.389 ms/op
     p(99.9900) =     17.991 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 5.533 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.139 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.011 ms/op
Iteration   1: 4.001 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  14.765 ms/op
                 listUser·p0.9999: 23.397 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   2: 4.087 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   7.182 ms/op
                 listUser·p0.999:  15.295 ms/op
                 listUser·p0.9999: 23.803 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   3: 4.115 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  17.236 ms/op
                 listUser·p0.9999: 21.583 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235919
  mean =      4.067 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1783 
    [ 2.500,  5.000) = 202978 
    [ 5.000,  7.500) = 29521 
    [ 7.500, 10.000) = 1191 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      7.143 ms/op
     p(99.9000) =     15.533 ms/op
     p(99.9900) =     23.259 ms/op
     p(99.9990) =     25.173 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.121 ± 3.254  ops/ms
ClientGrpc.existUser                       thrpt       3  10.613 ± 0.750  ops/ms
ClientGrpc.getUser                         thrpt       3  10.248 ± 1.322  ops/ms
ClientGrpc.listUser                        thrpt       3   7.906 ± 0.874  ops/ms
ClientGrpc.createUser                       avgt       3   3.160 ± 1.460   ms/op
ClientGrpc.existUser                        avgt       3   3.028 ± 0.343   ms/op
ClientGrpc.getUser                          avgt       3   3.159 ± 0.595   ms/op
ClientGrpc.listUser                         avgt       3   4.053 ± 0.941   ms/op
ClientGrpc.createUser                     sample  296922   3.231 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.617           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.199           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.112           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.307           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.694           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.921           ms/op
ClientGrpc.existUser                      sample  316948   3.029 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.737           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.834           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.521           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.097           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.462           ms/op
ClientGrpc.getUser                        sample  305310   3.143 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.593           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.389           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.991           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.038           ms/op
ClientGrpc.listUser                       sample  235919   4.067 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.976           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.243           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.143           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.533           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.259           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.264           ms/op
