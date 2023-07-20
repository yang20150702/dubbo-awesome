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
# Warmup Iteration   1: 3.760 ops/ms
# Warmup Iteration   2: 8.636 ops/ms
# Warmup Iteration   3: 9.739 ops/ms
Iteration   1: 10.301 ops/ms
Iteration   2: 10.430 ops/ms
Iteration   3: 10.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.333 ±(99.9%) 1.552 ops/ms [Average]
  (min, avg, max) = (10.269, 10.333, 10.430), stdev = 0.085
  CI (99.9%): [8.781, 11.885] (assumes normal distribution)


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
# Warmup Iteration   1: 7.270 ops/ms
# Warmup Iteration   2: 10.099 ops/ms
# Warmup Iteration   3: 10.731 ops/ms
Iteration   1: 10.847 ops/ms
Iteration   2: 10.892 ops/ms
Iteration   3: 10.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.846 ±(99.9%) 0.840 ops/ms [Average]
  (min, avg, max) = (10.800, 10.846, 10.892), stdev = 0.046
  CI (99.9%): [10.006, 11.687] (assumes normal distribution)


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
# Warmup Iteration   1: 6.963 ops/ms
# Warmup Iteration   2: 9.904 ops/ms
# Warmup Iteration   3: 10.218 ops/ms
Iteration   1: 10.322 ops/ms
Iteration   2: 10.342 ops/ms
Iteration   3: 10.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.318 ±(99.9%) 0.485 ops/ms [Average]
  (min, avg, max) = (10.289, 10.318, 10.342), stdev = 0.027
  CI (99.9%): [9.832, 10.803] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.380 ops/ms
# Warmup Iteration   2: 7.741 ops/ms
# Warmup Iteration   3: 7.832 ops/ms
Iteration   1: 8.002 ops/ms
Iteration   2: 8.013 ops/ms
Iteration   3: 7.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.974 ±(99.9%) 1.048 ops/ms [Average]
  (min, avg, max) = (7.908, 7.974, 8.013), stdev = 0.057
  CI (99.9%): [6.926, 9.023] (assumes normal distribution)


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
# Warmup Iteration   1: 4.284 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.191 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.002 ms/op
Iteration   1: 3.055 ±(99.9%) 0.002 ms/op
Iteration   2: 3.119 ±(99.9%) 0.002 ms/op
Iteration   3: 3.046 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.073 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (3.046, 3.073, 3.119), stdev = 0.040
  CI (99.9%): [2.350, 3.796] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.880 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.003 ms/op
Iteration   1: 2.986 ±(99.9%) 0.003 ms/op
Iteration   2: 2.960 ±(99.9%) 0.003 ms/op
Iteration   3: 2.978 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.974 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (2.960, 2.974, 2.986), stdev = 0.013
  CI (99.9%): [2.730, 3.219] (assumes normal distribution)


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
# Warmup Iteration   1: 4.074 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.003 ms/op
Iteration   1: 3.107 ±(99.9%) 0.004 ms/op
Iteration   2: 3.097 ±(99.9%) 0.008 ms/op
Iteration   3: 3.098 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.101 ±(99.9%) 0.097 ms/op [Average]
  (min, avg, max) = (3.097, 3.101, 3.107), stdev = 0.005
  CI (99.9%): [3.004, 3.198] (assumes normal distribution)


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
# Warmup Iteration   1: 5.174 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.022 ms/op
Iteration   1: 3.984 ±(99.9%) 0.011 ms/op
Iteration   2: 4.024 ±(99.9%) 0.015 ms/op
Iteration   3: 3.900 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.969 ±(99.9%) 1.159 ms/op [Average]
  (min, avg, max) = (3.900, 3.969, 4.024), stdev = 0.064
  CI (99.9%): [2.810, 5.129] (assumes normal distribution)


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
# Warmup Iteration   1: 4.447 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.006 ms/op
Iteration   1: 3.095 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  8.401 ms/op
                 createUser·p0.9999: 11.719 ms/op
                 createUser·p1.00:   12.124 ms/op

Iteration   2: 3.131 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.609 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  9.068 ms/op
                 createUser·p0.9999: 15.220 ms/op
                 createUser·p1.00:   15.516 ms/op

Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  13.370 ms/op
                 createUser·p0.9999: 18.678 ms/op
                 createUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308580
  mean =      3.111 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 695 
    [ 1.250,  2.500) = 14553 
    [ 2.500,  3.750) = 272361 
    [ 3.750,  5.000) = 19117 
    [ 5.000,  6.250) = 1044 
    [ 6.250,  7.500) = 304 
    [ 7.500,  8.750) = 183 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =      8.887 ms/op
     p(99.9900) =     17.835 ms/op
     p(99.9990) =     18.872 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.062 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
Iteration   1: 2.977 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  6.555 ms/op
                 existUser·p0.9999: 11.833 ms/op
                 existUser·p1.00:   12.206 ms/op

Iteration   2: 2.999 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.254 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  9.373 ms/op
                 existUser·p0.9999: 22.042 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   3: 3.004 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.484 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 18.001 ms/op
                 existUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320565
  mean =      2.993 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25605 
    [ 2.500,  5.000) = 293407 
    [ 5.000,  7.500) = 1133 
    [ 7.500, 10.000) = 155 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.254 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.364 ms/op
     p(99.9900) =     19.780 ms/op
     p(99.9990) =     22.269 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.135 ±(99.9%) 0.006 ms/op
Iteration   1: 3.121 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  6.766 ms/op
                 getUser·p0.9999: 12.849 ms/op
                 getUser·p1.00:   13.418 ms/op

Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  7.471 ms/op
                 getUser·p0.9999: 24.996 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   3: 3.078 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.893 ms/op
                 getUser·p0.9999: 14.609 ms/op
                 getUser·p1.00:   15.712 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308252
  mean =      3.113 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17113 
    [ 2.500,  5.000) = 289222 
    [ 5.000,  7.500) = 1675 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      7.094 ms/op
     p(99.9900) =     24.271 ms/op
     p(99.9990) =     25.291 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 5.574 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.010 ms/op
Iteration   1: 4.025 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.022 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  12.551 ms/op
                 listUser·p0.9999: 22.386 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   2: 3.927 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  14.511 ms/op
                 listUser·p0.9999: 20.700 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   3: 3.919 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.933 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 20.567 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242567
  mean =      3.957 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2348 
    [ 2.500,  5.000) = 219641 
    [ 5.000,  7.500) = 19298 
    [ 7.500, 10.000) = 864 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.825 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     21.643 ms/op
     p(99.9990) =     22.746 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.333 ± 1.552  ops/ms
ClientGrpc.existUser                       thrpt       3  10.846 ± 0.840  ops/ms
ClientGrpc.getUser                         thrpt       3  10.318 ± 0.485  ops/ms
ClientGrpc.listUser                        thrpt       3   7.974 ± 1.048  ops/ms
ClientGrpc.createUser                       avgt       3   3.073 ± 0.723   ms/op
ClientGrpc.existUser                        avgt       3   2.974 ± 0.244   ms/op
ClientGrpc.getUser                          avgt       3   3.101 ± 0.097   ms/op
ClientGrpc.listUser                         avgt       3   3.969 ± 1.159   ms/op
ClientGrpc.createUser                     sample  308580   3.111 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.609           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.887           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.835           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.940           ms/op
ClientGrpc.existUser                      sample  320565   2.993 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.254           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.364           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.780           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.348           ms/op
ClientGrpc.getUser                        sample  308252   3.113 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.712           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.094           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.271           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.395           ms/op
ClientGrpc.listUser                       sample  242567   3.957 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.863           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.057           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.643           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.872           ms/op
