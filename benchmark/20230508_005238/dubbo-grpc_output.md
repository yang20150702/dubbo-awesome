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
# Warmup Iteration   1: 4.089 ops/ms
# Warmup Iteration   2: 8.890 ops/ms
# Warmup Iteration   3: 9.784 ops/ms
Iteration   1: 10.322 ops/ms
Iteration   2: 10.358 ops/ms
Iteration   3: 10.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.361 ±(99.9%) 0.732 ops/ms [Average]
  (min, avg, max) = (10.322, 10.361, 10.402), stdev = 0.040
  CI (99.9%): [9.629, 11.092] (assumes normal distribution)


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
# Warmup Iteration   1: 7.270 ops/ms
# Warmup Iteration   2: 10.587 ops/ms
# Warmup Iteration   3: 11.068 ops/ms
Iteration   1: 11.036 ops/ms
Iteration   2: 11.000 ops/ms
Iteration   3: 10.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.945 ±(99.9%) 2.315 ops/ms [Average]
  (min, avg, max) = (10.800, 10.945, 11.036), stdev = 0.127
  CI (99.9%): [8.630, 13.260] (assumes normal distribution)


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
# Warmup Iteration   1: 6.714 ops/ms
# Warmup Iteration   2: 10.413 ops/ms
# Warmup Iteration   3: 10.426 ops/ms
Iteration   1: 10.540 ops/ms
Iteration   2: 10.529 ops/ms
Iteration   3: 10.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.591 ±(99.9%) 1.786 ops/ms [Average]
  (min, avg, max) = (10.529, 10.591, 10.704), stdev = 0.098
  CI (99.9%): [8.805, 12.378] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.438 ops/ms
# Warmup Iteration   2: 7.974 ops/ms
# Warmup Iteration   3: 8.203 ops/ms
Iteration   1: 8.215 ops/ms
Iteration   2: 8.228 ops/ms
Iteration   3: 8.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.250 ±(99.9%) 0.908 ops/ms [Average]
  (min, avg, max) = (8.215, 8.250, 8.307), stdev = 0.050
  CI (99.9%): [7.342, 9.158] (assumes normal distribution)


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
# Warmup Iteration   1: 4.376 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
Iteration   1: 3.019 ±(99.9%) 0.002 ms/op
Iteration   2: 3.038 ±(99.9%) 0.003 ms/op
Iteration   3: 3.016 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.024 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (3.016, 3.024, 3.038), stdev = 0.012
  CI (99.9%): [2.802, 3.247] (assumes normal distribution)


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.828 ±(99.9%) 0.003 ms/op
Iteration   1: 2.853 ±(99.9%) 0.003 ms/op
Iteration   2: 2.758 ±(99.9%) 0.003 ms/op
Iteration   3: 2.906 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.839 ±(99.9%) 1.366 ms/op [Average]
  (min, avg, max) = (2.758, 2.839, 2.906), stdev = 0.075
  CI (99.9%): [1.472, 4.205] (assumes normal distribution)


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
# Warmup Iteration   1: 4.370 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.003 ms/op
Iteration   1: 2.991 ±(99.9%) 0.003 ms/op
Iteration   2: 2.948 ±(99.9%) 0.003 ms/op
Iteration   3: 2.992 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.977 ±(99.9%) 0.455 ms/op [Average]
  (min, avg, max) = (2.948, 2.977, 2.992), stdev = 0.025
  CI (99.9%): [2.522, 3.432] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.994 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.016 ms/op
Iteration   1: 3.886 ±(99.9%) 0.007 ms/op
Iteration   2: 3.879 ±(99.9%) 0.018 ms/op
Iteration   3: 3.967 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.911 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (3.879, 3.911, 3.967), stdev = 0.049
  CI (99.9%): [3.014, 4.807] (assumes normal distribution)


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
# Warmup Iteration   1: 4.375 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.152 ms/op
                 createUser·p0.9999: 16.430 ms/op
                 createUser·p1.00:   16.646 ms/op

Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.790 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.352 ms/op
                 createUser·p0.999:  10.109 ms/op
                 createUser·p0.9999: 16.509 ms/op
                 createUser·p1.00:   18.121 ms/op

Iteration   3: 3.093 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  12.993 ms/op
                 createUser·p0.9999: 17.596 ms/op
                 createUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314462
  mean =      3.051 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 225 
    [ 1.250,  2.500) = 16381 
    [ 2.500,  3.750) = 283053 
    [ 3.750,  5.000) = 13460 
    [ 5.000,  6.250) = 571 
    [ 6.250,  7.500) = 340 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 73 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 66 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =     11.626 ms/op
     p(99.9900) =     17.221 ms/op
     p(99.9990) =     17.947 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 3.937 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.930 ±(99.9%) 0.006 ms/op
Iteration   1: 2.816 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.646 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.387 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  6.662 ms/op
                 existUser·p0.9999: 12.708 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.958 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.996 ms/op
                 existUser·p0.9999: 16.089 ms/op
                 existUser·p1.00:   16.466 ms/op

Iteration   3: 2.894 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.291 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  7.356 ms/op
                 existUser·p0.9999: 16.774 ms/op
                 existUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332396
  mean =      2.888 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1451 
    [ 1.250,  2.500) = 37430 
    [ 2.500,  3.750) = 285831 
    [ 3.750,  5.000) = 6607 
    [ 5.000,  6.250) = 542 
    [ 6.250,  7.500) = 288 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 54 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.291 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.502 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =      6.870 ms/op
     p(99.9900) =     16.261 ms/op
     p(99.9990) =     17.140 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.447 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  7.510 ms/op
                 getUser·p0.9999: 13.443 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.657 ms/op
                 getUser·p0.9999: 18.759 ms/op
                 getUser·p1.00:   19.562 ms/op

Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  8.024 ms/op
                 getUser·p0.9999: 21.904 ms/op
                 getUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318038
  mean =      3.020 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26198 
    [ 2.500,  5.000) = 290388 
    [ 5.000,  7.500) = 1102 
    [ 7.500, 10.000) = 151 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.725 ms/op
     p(99.9900) =     21.142 ms/op
     p(99.9990) =     23.248 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 5.225 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.011 ms/op
Iteration   1: 3.960 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  14.845 ms/op
                 listUser·p0.9999: 21.886 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   2: 3.900 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  15.041 ms/op
                 listUser·p0.9999: 25.061 ms/op
                 listUser·p1.00:   27.886 ms/op

Iteration   3: 3.933 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.934 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  22.153 ms/op
                 listUser·p0.9999: 27.974 ms/op
                 listUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244360
  mean =      3.931 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2904 
    [ 2.500,  5.000) = 220283 
    [ 5.000,  7.500) = 19777 
    [ 7.500, 10.000) = 926 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     15.984 ms/op
     p(99.9900) =     27.165 ms/op
     p(99.9990) =     28.574 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.361 ± 0.732  ops/ms
ClientGrpc.existUser                       thrpt       3  10.945 ± 2.315  ops/ms
ClientGrpc.getUser                         thrpt       3  10.591 ± 1.786  ops/ms
ClientGrpc.listUser                        thrpt       3   8.250 ± 0.908  ops/ms
ClientGrpc.createUser                       avgt       3   3.024 ± 0.222   ms/op
ClientGrpc.existUser                        avgt       3   2.839 ± 1.366   ms/op
ClientGrpc.getUser                          avgt       3   2.977 ± 0.455   ms/op
ClientGrpc.listUser                         avgt       3   3.911 ± 0.896   ms/op
ClientGrpc.createUser                     sample  314462   3.051 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.668           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.626           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.221           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.121           ms/op
ClientGrpc.existUser                      sample  332396   2.888 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.291           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.314           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.071           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.870           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.261           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.334           ms/op
ClientGrpc.getUser                        sample  318038   3.020 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.708           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.725           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.142           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.527           ms/op
ClientGrpc.listUser                       sample  244360   3.931 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.934           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.984           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.165           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.606           ms/op
