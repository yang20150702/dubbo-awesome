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
# Warmup Iteration   1: 4.213 ops/ms
# Warmup Iteration   2: 8.679 ops/ms
# Warmup Iteration   3: 9.622 ops/ms
Iteration   1: 9.820 ops/ms
Iteration   2: 9.855 ops/ms
Iteration   3: 10.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.903 ±(99.9%) 2.115 ops/ms [Average]
  (min, avg, max) = (9.820, 9.903, 10.036), stdev = 0.116
  CI (99.9%): [7.789, 12.018] (assumes normal distribution)


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
# Warmup Iteration   1: 7.009 ops/ms
# Warmup Iteration   2: 10.019 ops/ms
# Warmup Iteration   3: 10.280 ops/ms
Iteration   1: 10.584 ops/ms
Iteration   2: 10.483 ops/ms
Iteration   3: 10.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.531 ±(99.9%) 0.927 ops/ms [Average]
  (min, avg, max) = (10.483, 10.531, 10.584), stdev = 0.051
  CI (99.9%): [9.604, 11.458] (assumes normal distribution)


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
# Warmup Iteration   1: 7.596 ops/ms
# Warmup Iteration   2: 9.637 ops/ms
# Warmup Iteration   3: 9.922 ops/ms
Iteration   1: 9.930 ops/ms
Iteration   2: 10.101 ops/ms
Iteration   3: 9.959 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.997 ±(99.9%) 1.671 ops/ms [Average]
  (min, avg, max) = (9.930, 9.997, 10.101), stdev = 0.092
  CI (99.9%): [8.326, 11.667] (assumes normal distribution)


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
# Warmup Iteration   1: 5.341 ops/ms
# Warmup Iteration   2: 7.319 ops/ms
# Warmup Iteration   3: 7.564 ops/ms
Iteration   1: 7.777 ops/ms
Iteration   2: 7.680 ops/ms
Iteration   3: 7.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.770 ±(99.9%) 1.591 ops/ms [Average]
  (min, avg, max) = (7.680, 7.770, 7.854), stdev = 0.087
  CI (99.9%): [6.180, 9.361] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.595 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.003 ms/op
Iteration   1: 3.201 ±(99.9%) 0.004 ms/op
Iteration   2: 3.215 ±(99.9%) 0.002 ms/op
Iteration   3: 3.268 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.228 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (3.201, 3.228, 3.268), stdev = 0.035
  CI (99.9%): [2.582, 3.874] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.003 ms/op
Iteration   1: 3.037 ±(99.9%) 0.003 ms/op
Iteration   2: 3.085 ±(99.9%) 0.001 ms/op
Iteration   3: 3.091 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.071 ±(99.9%) 0.538 ms/op [Average]
  (min, avg, max) = (3.037, 3.071, 3.091), stdev = 0.030
  CI (99.9%): [2.533, 3.610] (assumes normal distribution)


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
# Warmup Iteration   1: 4.591 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.002 ms/op
Iteration   1: 3.227 ±(99.9%) 0.002 ms/op
Iteration   2: 3.175 ±(99.9%) 0.001 ms/op
Iteration   3: 3.218 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.207 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (3.175, 3.207, 3.227), stdev = 0.028
  CI (99.9%): [2.700, 3.714] (assumes normal distribution)


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
# Warmup Iteration   1: 4.970 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.332 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.038 ms/op
Iteration   1: 4.022 ±(99.9%) 0.008 ms/op
Iteration   2: 4.112 ±(99.9%) 0.006 ms/op
Iteration   3: 4.044 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.059 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (4.022, 4.059, 4.112), stdev = 0.047
  CI (99.9%): [3.205, 4.914] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.674 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.353 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.008 ms/op
Iteration   1: 3.240 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.618 ms/op
                 createUser·p0.9999: 16.843 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   2: 3.272 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.618 ms/op
                 createUser·p0.9999: 18.890 ms/op
                 createUser·p1.00:   19.399 ms/op

Iteration   3: 3.241 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  11.278 ms/op
                 createUser·p0.9999: 23.761 ms/op
                 createUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 295021
  mean =      3.251 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17350 
    [ 2.500,  5.000) = 276499 
    [ 5.000,  7.500) = 838 
    [ 7.500, 10.000) = 99 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.921 ms/op
     p(99.9900) =     23.282 ms/op
     p(99.9990) =     24.317 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.007 ms/op
Iteration   1: 3.125 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.207 ms/op
                 existUser·p0.9999: 14.693 ms/op
                 existUser·p1.00:   15.090 ms/op

Iteration   2: 2.926 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  7.336 ms/op
                 existUser·p0.9999: 23.857 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.494 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.599 ms/op
                 existUser·p0.9999: 17.087 ms/op
                 existUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317119
  mean =      3.028 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37863 
    [ 2.500,  5.000) = 278266 
    [ 5.000,  7.500) = 740 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.143 ms/op
     p(99.9900) =     22.980 ms/op
     p(99.9990) =     24.264 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 4.648 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.209 ±(99.9%) 0.008 ms/op
Iteration   1: 3.200 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.103 ms/op
                 getUser·p0.9999: 21.332 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   2: 3.223 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.732 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.891 ms/op
                 getUser·p0.9999: 21.401 ms/op
                 getUser·p1.00:   21.692 ms/op

Iteration   3: 3.217 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.454 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.112 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.781 ms/op
                 getUser·p0.9999: 29.854 ms/op
                 getUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 298778
  mean =      3.213 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13728 
    [ 2.500,  5.000) = 284112 
    [ 5.000,  7.500) = 669 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.454 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.327 ms/op
     p(99.9900) =     28.614 ms/op
     p(99.9990) =     30.081 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


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
# Warmup Iteration   1: 5.572 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.424 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.229 ±(99.9%) 0.012 ms/op
Iteration   1: 4.269 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.354 ms/op
                 listUser·p0.50:   4.055 ms/op
                 listUser·p0.90:   5.505 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  13.318 ms/op
                 listUser·p0.9999: 16.892 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   2: 4.172 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   3.985 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  14.309 ms/op
                 listUser·p0.9999: 22.894 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   3: 4.221 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 26.878 ms/op
                 listUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 227557
  mean =      4.220 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1302 
    [ 2.500,  5.000) = 190184 
    [ 5.000,  7.500) = 34290 
    [ 7.500, 10.000) = 1292 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      4.018 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     14.090 ms/op
     p(99.9900) =     25.247 ms/op
     p(99.9990) =     27.147 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.903 ± 2.115  ops/ms
ClientGrpc.existUser                       thrpt       3  10.531 ± 0.927  ops/ms
ClientGrpc.getUser                         thrpt       3   9.997 ± 1.671  ops/ms
ClientGrpc.listUser                        thrpt       3   7.770 ± 1.591  ops/ms
ClientGrpc.createUser                       avgt       3   3.228 ± 0.646   ms/op
ClientGrpc.existUser                        avgt       3   3.071 ± 0.538   ms/op
ClientGrpc.getUser                          avgt       3   3.207 ± 0.507   ms/op
ClientGrpc.listUser                         avgt       3   4.059 ± 0.854   ms/op
ClientGrpc.createUser                     sample  295021   3.251 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.674           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.207           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.981           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.166           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.921           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.282           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.740           ms/op
ClientGrpc.existUser                      sample  317119   3.028 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.494           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.912           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.143           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.980           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.379           ms/op
ClientGrpc.getUser                        sample  298778   3.213 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.454           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.178           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.327           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.614           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.147           ms/op
ClientGrpc.listUser                       sample  227557   4.220 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.869           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.018           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.947           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.258           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.090           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.247           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.230           ms/op
