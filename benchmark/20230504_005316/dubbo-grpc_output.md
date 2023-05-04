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
# Warmup Iteration   1: 4.333 ops/ms
# Warmup Iteration   2: 9.008 ops/ms
# Warmup Iteration   3: 10.194 ops/ms
Iteration   1: 10.818 ops/ms
Iteration   2: 10.492 ops/ms
Iteration   3: 10.843 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.718 ±(99.9%) 3.575 ops/ms [Average]
  (min, avg, max) = (10.492, 10.718, 10.843), stdev = 0.196
  CI (99.9%): [7.143, 14.292] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.628 ops/ms
# Warmup Iteration   2: 10.861 ops/ms
# Warmup Iteration   3: 11.134 ops/ms
Iteration   1: 11.363 ops/ms
Iteration   2: 11.431 ops/ms
Iteration   3: 11.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.351 ±(99.9%) 1.581 ops/ms [Average]
  (min, avg, max) = (11.259, 11.351, 11.431), stdev = 0.087
  CI (99.9%): [9.770, 12.932] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.153 ops/ms
# Warmup Iteration   2: 10.280 ops/ms
# Warmup Iteration   3: 10.646 ops/ms
Iteration   1: 10.739 ops/ms
Iteration   2: 10.659 ops/ms
Iteration   3: 10.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.672 ±(99.9%) 1.124 ops/ms [Average]
  (min, avg, max) = (10.618, 10.672, 10.739), stdev = 0.062
  CI (99.9%): [9.548, 11.796] (assumes normal distribution)


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
# Warmup Iteration   1: 5.397 ops/ms
# Warmup Iteration   2: 7.848 ops/ms
# Warmup Iteration   3: 8.287 ops/ms
Iteration   1: 8.137 ops/ms
Iteration   2: 8.059 ops/ms
Iteration   3: 8.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.103 ±(99.9%) 0.730 ops/ms [Average]
  (min, avg, max) = (8.059, 8.103, 8.137), stdev = 0.040
  CI (99.9%): [7.373, 8.834] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.278 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.003 ms/op
Iteration   1: 3.010 ±(99.9%) 0.003 ms/op
Iteration   2: 3.014 ±(99.9%) 0.002 ms/op
Iteration   3: 2.988 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.004 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (2.988, 3.004, 3.014), stdev = 0.014
  CI (99.9%): [2.744, 3.264] (assumes normal distribution)


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
# Warmup Iteration   1: 4.087 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.949 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.889 ±(99.9%) 0.002 ms/op
Iteration   1: 2.862 ±(99.9%) 0.002 ms/op
Iteration   2: 2.865 ±(99.9%) 0.002 ms/op
Iteration   3: 2.820 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.849 ±(99.9%) 0.457 ms/op [Average]
  (min, avg, max) = (2.820, 2.849, 2.865), stdev = 0.025
  CI (99.9%): [2.392, 3.306] (assumes normal distribution)


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
# Warmup Iteration   1: 4.126 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.003 ms/op
Iteration   1: 2.963 ±(99.9%) 0.004 ms/op
Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
Iteration   3: 3.000 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.983 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (2.963, 2.983, 3.000), stdev = 0.018
  CI (99.9%): [2.650, 3.315] (assumes normal distribution)


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
# Warmup Iteration   1: 4.692 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.906 ±(99.9%) 0.014 ms/op
Iteration   1: 3.928 ±(99.9%) 0.020 ms/op
Iteration   2: 3.877 ±(99.9%) 0.014 ms/op
Iteration   3: 3.923 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.909 ±(99.9%) 0.518 ms/op [Average]
  (min, avg, max) = (3.877, 3.909, 3.928), stdev = 0.028
  CI (99.9%): [3.391, 4.428] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.986 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.005 ms/op
Iteration   1: 3.048 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.454 ms/op
                 createUser·p0.999:  7.456 ms/op
                 createUser·p0.9999: 12.133 ms/op
                 createUser·p1.00:   12.354 ms/op

Iteration   2: 2.984 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.334 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.555 ms/op
                 createUser·p0.99:   4.182 ms/op
                 createUser·p0.999:  9.093 ms/op
                 createUser·p0.9999: 15.815 ms/op
                 createUser·p1.00:   16.007 ms/op

Iteration   3: 2.926 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  10.341 ms/op
                 createUser·p0.9999: 15.207 ms/op
                 createUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321719
  mean =      2.985 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1599 
    [ 1.250,  2.500) = 26527 
    [ 2.500,  3.750) = 278037 
    [ 3.750,  5.000) = 14230 
    [ 5.000,  6.250) = 673 
    [ 6.250,  7.500) = 282 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 75 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.334 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      8.999 ms/op
     p(99.9900) =     15.608 ms/op
     p(99.9990) =     16.442 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.886 ±(99.9%) 0.005 ms/op
Iteration   1: 2.874 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.445 ms/op
                 existUser·p0.99:   3.926 ms/op
                 existUser·p0.999:  6.267 ms/op
                 existUser·p0.9999: 15.411 ms/op
                 existUser·p1.00:   17.334 ms/op

Iteration   2: 2.957 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.031 ms/op
                 existUser·p0.999:  6.923 ms/op
                 existUser·p0.9999: 13.162 ms/op
                 existUser·p1.00:   15.139 ms/op

Iteration   3: 2.863 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.301 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.889 ms/op
                 existUser·p0.9999: 17.361 ms/op
                 existUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331433
  mean =      2.897 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1318 
    [ 1.250,  2.500) = 39005 
    [ 2.500,  3.750) = 283538 
    [ 3.750,  5.000) = 6594 
    [ 5.000,  6.250) = 570 
    [ 6.250,  7.500) = 172 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.301 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.527 ms/op
     p(99.0000) =      4.100 ms/op
     p(99.9000) =      6.768 ms/op
     p(99.9900) =     16.876 ms/op
     p(99.9990) =     17.465 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.007 ms/op
Iteration   1: 2.994 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.572 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  8.029 ms/op
                 getUser·p0.9999: 12.478 ms/op
                 getUser·p1.00:   12.747 ms/op

Iteration   2: 3.033 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  6.644 ms/op
                 getUser·p0.9999: 13.861 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   3: 3.059 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.855 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.162 ms/op
                 getUser·p0.999:  6.832 ms/op
                 getUser·p0.9999: 16.876 ms/op
                 getUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317090
  mean =      3.028 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 377 
    [ 1.250,  2.500) = 19812 
    [ 2.500,  3.750) = 284141 
    [ 3.750,  5.000) = 11635 
    [ 5.000,  6.250) = 674 
    [ 6.250,  7.500) = 197 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.829 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.905 ms/op
     p(99.9900) =     14.633 ms/op
     p(99.9990) =     17.126 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 5.876 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.011 ms/op
Iteration   1: 3.923 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.741 ms/op
                 listUser·p0.999:  13.287 ms/op
                 listUser·p0.9999: 20.366 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   2: 3.880 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  14.280 ms/op
                 listUser·p0.9999: 17.367 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   3: 3.857 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.777 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  17.924 ms/op
                 listUser·p0.9999: 25.100 ms/op
                 listUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247107
  mean =      3.886 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3685 
    [ 2.500,  5.000) = 223597 
    [ 5.000,  7.500) = 18691 
    [ 7.500, 10.000) = 730 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     14.402 ms/op
     p(99.9900) =     24.254 ms/op
     p(99.9990) =     25.314 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.718 ± 3.575  ops/ms
ClientGrpc.existUser                       thrpt       3  11.351 ± 1.581  ops/ms
ClientGrpc.getUser                         thrpt       3  10.672 ± 1.124  ops/ms
ClientGrpc.listUser                        thrpt       3   8.103 ± 0.730  ops/ms
ClientGrpc.createUser                       avgt       3   3.004 ± 0.260   ms/op
ClientGrpc.existUser                        avgt       3   2.849 ± 0.457   ms/op
ClientGrpc.getUser                          avgt       3   2.983 ± 0.332   ms/op
ClientGrpc.listUser                         avgt       3   3.909 ± 0.518   ms/op
ClientGrpc.createUser                     sample  321719   2.985 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.334           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.486           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.999           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.608           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.695           ms/op
ClientGrpc.existUser                      sample  331433   2.897 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.301           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.100           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.768           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.876           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.465           ms/op
ClientGrpc.getUser                        sample  317090   3.028 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.829           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.905           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.633           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.269           ms/op
ClientGrpc.listUser                       sample  247107   3.886 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.777           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.489           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.402           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.254           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.214           ms/op
