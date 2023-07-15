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
# Warmup Iteration   1: 4.271 ops/ms
# Warmup Iteration   2: 8.971 ops/ms
# Warmup Iteration   3: 10.182 ops/ms
Iteration   1: 10.265 ops/ms
Iteration   2: 10.452 ops/ms
Iteration   3: 10.652 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.456 ±(99.9%) 3.534 ops/ms [Average]
  (min, avg, max) = (10.265, 10.456, 10.652), stdev = 0.194
  CI (99.9%): [6.923, 13.990] (assumes normal distribution)


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
# Warmup Iteration   1: 7.850 ops/ms
# Warmup Iteration   2: 10.641 ops/ms
# Warmup Iteration   3: 10.956 ops/ms
Iteration   1: 10.698 ops/ms
Iteration   2: 11.066 ops/ms
Iteration   3: 11.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.963 ±(99.9%) 4.226 ops/ms [Average]
  (min, avg, max) = (10.698, 10.963, 11.126), stdev = 0.232
  CI (99.9%): [6.737, 15.190] (assumes normal distribution)


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
# Warmup Iteration   1: 6.684 ops/ms
# Warmup Iteration   2: 9.915 ops/ms
# Warmup Iteration   3: 10.481 ops/ms
Iteration   1: 10.335 ops/ms
Iteration   2: 10.368 ops/ms
Iteration   3: 10.463 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.388 ±(99.9%) 1.212 ops/ms [Average]
  (min, avg, max) = (10.335, 10.388, 10.463), stdev = 0.066
  CI (99.9%): [9.176, 11.600] (assumes normal distribution)


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
# Warmup Iteration   1: 5.582 ops/ms
# Warmup Iteration   2: 7.979 ops/ms
# Warmup Iteration   3: 7.984 ops/ms
Iteration   1: 8.065 ops/ms
Iteration   2: 8.222 ops/ms
Iteration   3: 8.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.143 ±(99.9%) 1.440 ops/ms [Average]
  (min, avg, max) = (8.065, 8.143, 8.222), stdev = 0.079
  CI (99.9%): [6.702, 9.583] (assumes normal distribution)


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.005 ms/op
Iteration   1: 3.054 ±(99.9%) 0.002 ms/op
Iteration   2: 3.006 ±(99.9%) 0.001 ms/op
Iteration   3: 3.050 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.037 ±(99.9%) 0.491 ms/op [Average]
  (min, avg, max) = (3.006, 3.037, 3.054), stdev = 0.027
  CI (99.9%): [2.545, 3.528] (assumes normal distribution)


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
# Warmup Iteration   1: 3.499 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.873 ±(99.9%) 0.003 ms/op
Iteration   1: 2.830 ±(99.9%) 0.002 ms/op
Iteration   2: 2.876 ±(99.9%) 0.003 ms/op
Iteration   3: 2.921 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.876 ±(99.9%) 0.828 ms/op [Average]
  (min, avg, max) = (2.830, 2.876, 2.921), stdev = 0.045
  CI (99.9%): [2.047, 3.704] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.312 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.003 ms/op
Iteration   1: 3.021 ±(99.9%) 0.004 ms/op
Iteration   2: 3.048 ±(99.9%) 0.001 ms/op
Iteration   3: 3.012 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.027 ±(99.9%) 0.340 ms/op [Average]
  (min, avg, max) = (3.012, 3.027, 3.048), stdev = 0.019
  CI (99.9%): [2.687, 3.367] (assumes normal distribution)


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
# Warmup Iteration   1: 5.348 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.043 ms/op
Iteration   1: 3.949 ±(99.9%) 0.034 ms/op
Iteration   2: 3.889 ±(99.9%) 0.025 ms/op
Iteration   3: 3.957 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.931 ±(99.9%) 0.677 ms/op [Average]
  (min, avg, max) = (3.889, 3.931, 3.957), stdev = 0.037
  CI (99.9%): [3.254, 4.608] (assumes normal distribution)


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
# Warmup Iteration   1: 4.395 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
Iteration   1: 3.061 ±(99.9%) 0.004 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  6.472 ms/op
                 createUser·p0.9999: 11.838 ms/op
                 createUser·p1.00:   12.108 ms/op

Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  10.797 ms/op
                 createUser·p0.9999: 18.022 ms/op
                 createUser·p1.00:   18.514 ms/op

Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.586 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  10.783 ms/op
                 createUser·p0.9999: 22.249 ms/op
                 createUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317317
  mean =      3.025 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19079 
    [ 2.500,  5.000) = 296855 
    [ 5.000,  7.500) = 1001 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.930 ms/op
     p(99.9900) =     20.677 ms/op
     p(99.9990) =     22.500 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.005 ms/op
Iteration   1: 2.925 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  6.518 ms/op
                 existUser·p0.9999: 12.617 ms/op
                 existUser·p1.00:   12.796 ms/op

Iteration   2: 2.900 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.574 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.404 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  11.108 ms/op
                 existUser·p0.9999: 15.809 ms/op
                 existUser·p1.00:   16.056 ms/op

Iteration   3: 2.931 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.377 ms/op
                 existUser·p0.9999: 16.908 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328706
  mean =      2.919 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 648 
    [ 1.250,  2.500) = 31378 
    [ 2.500,  3.750) = 290079 
    [ 3.750,  5.000) = 5333 
    [ 5.000,  6.250) = 560 
    [ 6.250,  7.500) = 318 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.574 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.318 ms/op
     p(95.0000) =      3.482 ms/op
     p(99.0000) =      4.125 ms/op
     p(99.9000) =      8.162 ms/op
     p(99.9900) =     16.550 ms/op
     p(99.9990) =     18.069 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 4.301 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.692 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  7.584 ms/op
                 getUser·p0.9999: 17.711 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   2: 3.092 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.475 ms/op
                 getUser·p0.9999: 14.417 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   3: 2.968 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  6.826 ms/op
                 getUser·p0.9999: 27.827 ms/op
                 getUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316629
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26217 
    [ 2.500,  5.000) = 288889 
    [ 5.000,  7.500) = 1225 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.417 ms/op
     p(99.9900) =     25.734 ms/op
     p(99.9990) =     28.115 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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
# Warmup Iteration   1: 5.149 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.986 ±(99.9%) 0.011 ms/op
Iteration   1: 3.863 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  13.455 ms/op
                 listUser·p0.9999: 21.987 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   2: 3.971 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.357 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  13.861 ms/op
                 listUser·p0.9999: 15.591 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   3: 3.891 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.727 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  15.677 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245715
  mean =      3.908 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2906 
    [ 2.500,  5.000) = 223817 
    [ 5.000,  7.500) = 17804 
    [ 7.500, 10.000) = 702 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.357 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     13.898 ms/op
     p(99.9900) =     21.393 ms/op
     p(99.9990) =     22.300 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.456 ± 3.534  ops/ms
ClientGrpc.existUser                       thrpt       3  10.963 ± 4.226  ops/ms
ClientGrpc.getUser                         thrpt       3  10.388 ± 1.212  ops/ms
ClientGrpc.listUser                        thrpt       3   8.143 ± 1.440  ops/ms
ClientGrpc.createUser                       avgt       3   3.037 ± 0.491   ms/op
ClientGrpc.existUser                        avgt       3   2.876 ± 0.828   ms/op
ClientGrpc.getUser                          avgt       3   3.027 ± 0.340   ms/op
ClientGrpc.listUser                         avgt       3   3.931 ± 0.677   ms/op
ClientGrpc.createUser                     sample  317317   3.025 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.586           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.478           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.930           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.677           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.643           ms/op
ClientGrpc.existUser                      sample  328706   2.919 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.574           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.125           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.162           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.550           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.743           ms/op
ClientGrpc.getUser                        sample  316629   3.033 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.692           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.417           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.734           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.180           ms/op
ClientGrpc.listUser                       sample  245715   3.908 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.357           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.809           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.448           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.898           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.393           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.381           ms/op
