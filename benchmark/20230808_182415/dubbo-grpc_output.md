# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.153 ops/ms
# Warmup Iteration   2: 7.904 ops/ms
# Warmup Iteration   3: 8.972 ops/ms
Iteration   1: 9.255 ops/ms
Iteration   2: 9.224 ops/ms
Iteration   3: 9.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.335 ±(99.9%) 3.021 ops/ms [Average]
  (min, avg, max) = (9.224, 9.335, 9.525), stdev = 0.166
  CI (99.9%): [6.314, 12.356] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.029 ops/ms
# Warmup Iteration   2: 9.166 ops/ms
# Warmup Iteration   3: 9.384 ops/ms
Iteration   1: 9.997 ops/ms
Iteration   2: 9.798 ops/ms
Iteration   3: 10.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.933 ±(99.9%) 2.134 ops/ms [Average]
  (min, avg, max) = (9.798, 9.933, 10.004), stdev = 0.117
  CI (99.9%): [7.799, 12.067] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.082 ops/ms
# Warmup Iteration   2: 9.113 ops/ms
# Warmup Iteration   3: 9.536 ops/ms
Iteration   1: 9.669 ops/ms
Iteration   2: 9.749 ops/ms
Iteration   3: 9.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.655 ±(99.9%) 1.847 ops/ms [Average]
  (min, avg, max) = (9.548, 9.655, 9.749), stdev = 0.101
  CI (99.9%): [7.808, 11.503] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 4.648 ops/ms
# Warmup Iteration   2: 6.852 ops/ms
# Warmup Iteration   3: 6.906 ops/ms
Iteration   1: 7.284 ops/ms
Iteration   2: 7.337 ops/ms
Iteration   3: 7.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.218 ±(99.9%) 2.977 ops/ms [Average]
  (min, avg, max) = (7.032, 7.218, 7.337), stdev = 0.163
  CI (99.9%): [4.240, 10.195] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.781 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.572 ±(99.9%) 0.003 ms/op
Iteration   1: 3.407 ±(99.9%) 0.002 ms/op
Iteration   2: 3.524 ±(99.9%) 0.002 ms/op
Iteration   3: 3.469 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.467 ±(99.9%) 1.069 ms/op [Average]
  (min, avg, max) = (3.407, 3.467, 3.524), stdev = 0.059
  CI (99.9%): [2.399, 4.536] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.204 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.321 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.002 ms/op
Iteration   1: 3.208 ±(99.9%) 0.001 ms/op
Iteration   2: 3.197 ±(99.9%) 0.002 ms/op
Iteration   3: 3.185 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.197 ±(99.9%) 0.214 ms/op [Average]
  (min, avg, max) = (3.185, 3.197, 3.208), stdev = 0.012
  CI (99.9%): [2.983, 3.411] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.700 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.421 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.004 ms/op
Iteration   1: 3.313 ±(99.9%) 0.002 ms/op
Iteration   2: 3.307 ±(99.9%) 0.002 ms/op
Iteration   3: 3.272 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.297 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (3.272, 3.297, 3.313), stdev = 0.022
  CI (99.9%): [2.893, 3.702] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.358 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.552 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.361 ±(99.9%) 0.025 ms/op
Iteration   1: 4.361 ±(99.9%) 0.023 ms/op
Iteration   2: 4.397 ±(99.9%) 0.011 ms/op
Iteration   3: 4.499 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.419 ±(99.9%) 1.307 ms/op [Average]
  (min, avg, max) = (4.361, 4.419, 4.499), stdev = 0.072
  CI (99.9%): [3.112, 5.726] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.561 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.007 ms/op
Iteration   1: 3.404 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  8.945 ms/op
                 createUser·p0.9999: 16.738 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   2: 3.370 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  10.502 ms/op
                 createUser·p0.9999: 22.216 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   3: 3.429 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  9.191 ms/op
                 createUser·p0.9999: 20.666 ms/op
                 createUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 282292
  mean =      3.401 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12785 
    [ 2.500,  5.000) = 264168 
    [ 5.000,  7.500) = 4483 
    [ 7.500, 10.000) = 604 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.695 ms/op
     p(99.9900) =     21.415 ms/op
     p(99.9990) =     22.583 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.579 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.222 ±(99.9%) 0.008 ms/op
Iteration   1: 3.026 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.735 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  8.064 ms/op
                 existUser·p0.9999: 13.025 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   2: 3.120 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.822 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.084 ms/op
                 existUser·p0.99:   4.994 ms/op
                 existUser·p0.999:  8.876 ms/op
                 existUser·p0.9999: 25.419 ms/op
                 existUser·p1.00:   25.690 ms/op

Iteration   3: 3.062 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.116 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  8.497 ms/op
                 existUser·p0.9999: 20.287 ms/op
                 existUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312682
  mean =      3.069 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37267 
    [ 2.500,  5.000) = 271888 
    [ 5.000,  7.500) = 2896 
    [ 7.500, 10.000) = 439 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      5.145 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     24.853 ms/op
     p(99.9990) =     25.620 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.674 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.534 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.008 ms/op
Iteration   1: 3.332 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.653 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   4.112 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   5.374 ms/op
                 getUser·p0.999:  10.273 ms/op
                 getUser·p0.9999: 13.681 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   2: 3.326 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  9.991 ms/op
                 getUser·p0.9999: 15.954 ms/op
                 getUser·p1.00:   16.253 ms/op

Iteration   3: 3.374 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   5.317 ms/op
                 getUser·p0.999:  10.519 ms/op
                 getUser·p0.9999: 18.776 ms/op
                 getUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 287022
  mean =      3.344 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 270 
    [ 1.250,  2.500) = 16165 
    [ 2.500,  3.750) = 210821 
    [ 3.750,  5.000) = 54778 
    [ 5.000,  6.250) = 3266 
    [ 6.250,  7.500) = 978 
    [ 7.500,  8.750) = 275 
    [ 8.750, 10.000) = 151 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      4.080 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     10.174 ms/op
     p(99.9900) =     18.153 ms/op
     p(99.9990) =     18.948 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.420 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.546 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.364 ±(99.9%) 0.013 ms/op
Iteration   1: 4.348 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   4.149 ms/op
                 listUser·p0.90:   5.669 ms/op
                 listUser·p0.95:   6.423 ms/op
                 listUser·p0.99:   8.341 ms/op
                 listUser·p0.999:  14.451 ms/op
                 listUser·p0.9999: 21.660 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   2: 4.345 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.229 ms/op
                 listUser·p0.50:   4.145 ms/op
                 listUser·p0.90:   5.628 ms/op
                 listUser·p0.95:   6.332 ms/op
                 listUser·p0.99:   7.998 ms/op
                 listUser·p0.999:  14.743 ms/op
                 listUser·p0.9999: 17.269 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   3: 4.320 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   4.125 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.234 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  16.806 ms/op
                 listUser·p0.9999: 25.690 ms/op
                 listUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 221375
  mean =      4.338 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2053 
    [ 2.500,  5.000) = 181538 
    [ 5.000,  7.500) = 34282 
    [ 7.500, 10.000) = 2678 
    [10.000, 12.500) = 364 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      4.141 ms/op
     p(90.0000) =      5.603 ms/op
     p(95.0000) =      6.332 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     15.526 ms/op
     p(99.9900) =     25.489 ms/op
     p(99.9990) =     27.202 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.335 ± 3.021  ops/ms
ClientGrpc.existUser                       thrpt       3   9.933 ± 2.134  ops/ms
ClientGrpc.getUser                         thrpt       3   9.655 ± 1.847  ops/ms
ClientGrpc.listUser                        thrpt       3   7.218 ± 2.977  ops/ms
ClientGrpc.createUser                       avgt       3   3.467 ± 1.069   ms/op
ClientGrpc.existUser                        avgt       3   3.197 ± 0.214   ms/op
ClientGrpc.getUser                          avgt       3   3.297 ± 0.404   ms/op
ClientGrpc.listUser                         avgt       3   4.419 ± 1.307   ms/op
ClientGrpc.createUser                     sample  282292   3.401 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.734           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.318           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.182           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.652           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.695           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.415           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.774           ms/op
ClientGrpc.existUser                      sample  312682   3.069 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.735           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.035           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.039           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.569           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.853           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.690           ms/op
ClientGrpc.getUser                        sample  287022   3.344 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.653           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.289           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.080           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.472           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.174           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.153           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.104           ms/op
ClientGrpc.listUser                       sample  221375   4.338 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.928           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.141           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.332           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.143           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.526           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.489           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.329           ms/op
