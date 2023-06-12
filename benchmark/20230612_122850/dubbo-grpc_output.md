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
# Warmup Iteration   1: 1.708 ops/ms
# Warmup Iteration   2: 4.398 ops/ms
# Warmup Iteration   3: 6.258 ops/ms
Iteration   1: 6.340 ops/ms
Iteration   2: 6.729 ops/ms
Iteration   3: 6.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.570 ±(99.9%) 3.723 ops/ms [Average]
  (min, avg, max) = (6.340, 6.570, 6.729), stdev = 0.204
  CI (99.9%): [2.847, 10.293] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.238 ops/ms
# Warmup Iteration   2: 6.269 ops/ms
# Warmup Iteration   3: 6.902 ops/ms
Iteration   1: 7.008 ops/ms
Iteration   2: 7.092 ops/ms
Iteration   3: 7.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.068 ±(99.9%) 0.941 ops/ms [Average]
  (min, avg, max) = (7.008, 7.068, 7.102), stdev = 0.052
  CI (99.9%): [6.126, 8.009] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.609 ops/ms
# Warmup Iteration   2: 6.084 ops/ms
# Warmup Iteration   3: 6.569 ops/ms
Iteration   1: 6.561 ops/ms
Iteration   2: 6.697 ops/ms
Iteration   3: 6.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.714 ±(99.9%) 2.948 ops/ms [Average]
  (min, avg, max) = (6.561, 6.714, 6.883), stdev = 0.162
  CI (99.9%): [3.766, 9.662] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.204 ops/ms
# Warmup Iteration   2: 4.700 ops/ms
# Warmup Iteration   3: 5.207 ops/ms
Iteration   1: 5.450 ops/ms
Iteration   2: 5.365 ops/ms
Iteration   3: 5.310 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.375 ±(99.9%) 1.289 ops/ms [Average]
  (min, avg, max) = (5.310, 5.375, 5.450), stdev = 0.071
  CI (99.9%): [4.086, 6.664] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.452 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.164 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.049 ±(99.9%) 0.014 ms/op
Iteration   1: 4.688 ±(99.9%) 0.004 ms/op
Iteration   2: 4.643 ±(99.9%) 0.005 ms/op
Iteration   3: 4.655 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.662 ±(99.9%) 0.420 ms/op [Average]
  (min, avg, max) = (4.643, 4.662, 4.688), stdev = 0.023
  CI (99.9%): [4.242, 5.082] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.871 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.797 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.435 ±(99.9%) 0.004 ms/op
Iteration   1: 4.409 ±(99.9%) 0.005 ms/op
Iteration   2: 4.419 ±(99.9%) 0.005 ms/op
Iteration   3: 4.328 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.385 ±(99.9%) 0.917 ms/op [Average]
  (min, avg, max) = (4.328, 4.385, 4.419), stdev = 0.050
  CI (99.9%): [3.469, 5.302] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.465 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.189 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.965 ±(99.9%) 0.005 ms/op
Iteration   1: 4.650 ±(99.9%) 0.008 ms/op
Iteration   2: 4.865 ±(99.9%) 0.008 ms/op
Iteration   3: 4.731 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.749 ±(99.9%) 1.978 ms/op [Average]
  (min, avg, max) = (4.650, 4.749, 4.865), stdev = 0.108
  CI (99.9%): [2.770, 6.727] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.997 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.672 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 6.183 ±(99.9%) 0.032 ms/op
Iteration   1: 6.144 ±(99.9%) 0.021 ms/op
Iteration   2: 6.161 ±(99.9%) 0.029 ms/op
Iteration   3: 6.047 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.117 ±(99.9%) 1.123 ms/op [Average]
  (min, avg, max) = (6.047, 6.117, 6.161), stdev = 0.062
  CI (99.9%): [4.994, 7.240] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.521 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.147 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.616 ±(99.9%) 0.017 ms/op
Iteration   1: 4.729 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   4.555 ms/op
                 createUser·p0.90:   6.103 ms/op
                 createUser·p0.95:   6.832 ms/op
                 createUser·p0.99:   8.864 ms/op
                 createUser·p0.999:  13.702 ms/op
                 createUser·p0.9999: 24.013 ms/op
                 createUser·p1.00:   24.838 ms/op

Iteration   2: 4.663 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   4.497 ms/op
                 createUser·p0.90:   5.906 ms/op
                 createUser·p0.95:   6.545 ms/op
                 createUser·p0.99:   8.998 ms/op
                 createUser·p0.999:  12.993 ms/op
                 createUser·p0.9999: 25.170 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   3: 4.712 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   4.555 ms/op
                 createUser·p0.90:   5.947 ms/op
                 createUser·p0.95:   6.496 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  15.608 ms/op
                 createUser·p0.9999: 29.577 ms/op
                 createUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 204262
  mean =      4.701 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3715 
    [ 2.500,  5.000) = 136970 
    [ 5.000,  7.500) = 58576 
    [ 7.500, 10.000) = 4113 
    [10.000, 12.500) = 565 
    [12.500, 15.000) = 160 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      4.538 ms/op
     p(90.0000) =      5.980 ms/op
     p(95.0000) =      6.619 ms/op
     p(99.0000) =      8.782 ms/op
     p(99.9000) =     13.795 ms/op
     p(99.9900) =     28.541 ms/op
     p(99.9990) =     31.010 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.627 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.811 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.457 ±(99.9%) 0.016 ms/op
Iteration   1: 4.229 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   4.108 ms/op
                 existUser·p0.90:   5.300 ms/op
                 existUser·p0.95:   5.841 ms/op
                 existUser·p0.99:   7.569 ms/op
                 existUser·p0.999:  13.844 ms/op
                 existUser·p0.9999: 18.266 ms/op
                 existUser·p1.00:   18.579 ms/op

Iteration   2: 4.428 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.108 ms/op
                 existUser·p0.50:   4.219 ms/op
                 existUser·p0.90:   5.661 ms/op
                 existUser·p0.95:   6.513 ms/op
                 existUser·p0.99:   9.224 ms/op
                 existUser·p0.999:  14.732 ms/op
                 existUser·p0.9999: 22.890 ms/op
                 existUser·p1.00:   23.364 ms/op

Iteration   3: 4.394 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.204 ms/op
                 existUser·p0.50:   4.194 ms/op
                 existUser·p0.90:   5.612 ms/op
                 existUser·p0.95:   6.447 ms/op
                 existUser·p0.99:   8.798 ms/op
                 existUser·p0.999:  14.780 ms/op
                 existUser·p0.9999: 26.477 ms/op
                 existUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 220783
  mean =      4.348 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7303 
    [ 2.500,  5.000) = 173726 
    [ 5.000,  7.500) = 35200 
    [ 7.500, 10.000) = 3448 
    [10.000, 12.500) = 599 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.108 ms/op
     p(50.0000) =      4.174 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.267 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     14.379 ms/op
     p(99.9900) =     25.390 ms/op
     p(99.9990) =     27.543 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.737 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 4.937 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.761 ±(99.9%) 0.017 ms/op
Iteration   1: 4.567 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   4.440 ms/op
                 getUser·p0.90:   5.669 ms/op
                 getUser·p0.95:   6.185 ms/op
                 getUser·p0.99:   8.004 ms/op
                 getUser·p0.999:  12.350 ms/op
                 getUser·p0.9999: 20.218 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   2: 4.608 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   4.432 ms/op
                 getUser·p0.90:   5.857 ms/op
                 getUser·p0.95:   6.545 ms/op
                 getUser·p0.99:   9.240 ms/op
                 getUser·p0.999:  14.287 ms/op
                 getUser·p0.9999: 23.331 ms/op
                 getUser·p1.00:   23.560 ms/op

Iteration   3: 4.616 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   4.440 ms/op
                 getUser·p0.90:   5.939 ms/op
                 getUser·p0.95:   6.644 ms/op
                 getUser·p0.99:   8.880 ms/op
                 getUser·p0.999:  14.556 ms/op
                 getUser·p0.9999: 24.513 ms/op
                 getUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 208895
  mean =      4.597 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4441 
    [ 2.500,  5.000) = 151272 
    [ 5.000,  7.500) = 48852 
    [ 7.500, 10.000) = 3344 
    [10.000, 12.500) = 682 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.808 ms/op
     p(95.0000) =      6.447 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     13.979 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.656 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 6.781 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 6.204 ±(99.9%) 0.027 ms/op
Iteration   1: 6.083 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   5.595 ms/op
                 listUser·p0.90:   8.618 ms/op
                 listUser·p0.95:   9.798 ms/op
                 listUser·p0.99:   12.567 ms/op
                 listUser·p0.999:  17.795 ms/op
                 listUser·p0.9999: 21.350 ms/op
                 listUser·p1.00:   26.280 ms/op

Iteration   2: 6.375 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   5.857 ms/op
                 listUser·p0.90:   8.995 ms/op
                 listUser·p0.95:   10.093 ms/op
                 listUser·p0.99:   13.238 ms/op
                 listUser·p0.999:  20.899 ms/op
                 listUser·p0.9999: 28.637 ms/op
                 listUser·p1.00:   29.458 ms/op

Iteration   3: 6.249 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.831 ms/op
                 listUser·p0.50:   5.800 ms/op
                 listUser·p0.90:   8.651 ms/op
                 listUser·p0.95:   9.732 ms/op
                 listUser·p0.99:   12.370 ms/op
                 listUser·p0.999:  22.249 ms/op
                 listUser·p0.9999: 31.409 ms/op
                 listUser·p1.00:   31.949 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 154046
  mean =      6.234 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 168 
    [ 2.500,  5.000) = 39170 
    [ 5.000,  7.500) = 83923 
    [ 7.500, 10.000) = 23608 
    [10.000, 12.500) = 5457 
    [12.500, 15.000) = 1135 
    [15.000, 17.500) = 335 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      5.743 ms/op
     p(90.0000) =      8.765 ms/op
     p(95.0000) =      9.880 ms/op
     p(99.0000) =     12.714 ms/op
     p(99.9000) =     19.756 ms/op
     p(99.9900) =     29.647 ms/op
     p(99.9990) =     31.878 ms/op
     p(99.9999) =     31.949 ms/op
    p(100.0000) =     31.949 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.570 ± 3.723  ops/ms
ClientGrpc.existUser                       thrpt       3   7.068 ± 0.941  ops/ms
ClientGrpc.getUser                         thrpt       3   6.714 ± 2.948  ops/ms
ClientGrpc.listUser                        thrpt       3   5.375 ± 1.289  ops/ms
ClientGrpc.createUser                       avgt       3   4.662 ± 0.420   ms/op
ClientGrpc.existUser                        avgt       3   4.385 ± 0.917   ms/op
ClientGrpc.getUser                          avgt       3   4.749 ± 1.978   ms/op
ClientGrpc.listUser                         avgt       3   6.117 ± 1.123   ms/op
ClientGrpc.createUser                     sample  204262   4.701 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.796           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.980           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.619           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.782           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.795           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.541           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.162           ms/op
ClientGrpc.existUser                      sample  220783   4.348 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.108           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.513           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.267           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.667           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.379           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.390           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.820           ms/op
ClientGrpc.getUser                        sample  208895   4.597 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.892           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.808           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.447           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.765           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.979           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.117           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.805           ms/op
ClientGrpc.listUser                       sample  154046   6.234 ± 0.017   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.374           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.765           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.880           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.714           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.756           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.647           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.949           ms/op
