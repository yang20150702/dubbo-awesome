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
# Warmup Iteration   1: 2.504 ops/ms
# Warmup Iteration   2: 6.070 ops/ms
# Warmup Iteration   3: 7.148 ops/ms
Iteration   1: 7.738 ops/ms
Iteration   2: 7.917 ops/ms
Iteration   3: 7.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.852 ±(99.9%) 1.811 ops/ms [Average]
  (min, avg, max) = (7.738, 7.852, 7.917), stdev = 0.099
  CI (99.9%): [6.041, 9.664] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.123 ops/ms
# Warmup Iteration   2: 7.629 ops/ms
# Warmup Iteration   3: 7.947 ops/ms
Iteration   1: 8.364 ops/ms
Iteration   2: 8.416 ops/ms
Iteration   3: 8.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.354 ±(99.9%) 1.221 ops/ms [Average]
  (min, avg, max) = (8.283, 8.354, 8.416), stdev = 0.067
  CI (99.9%): [7.133, 9.575] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.586 ops/ms
# Warmup Iteration   2: 7.016 ops/ms
# Warmup Iteration   3: 7.391 ops/ms
Iteration   1: 7.964 ops/ms
Iteration   2: 7.630 ops/ms
Iteration   3: 7.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.705 ±(99.9%) 4.216 ops/ms [Average]
  (min, avg, max) = (7.520, 7.705, 7.964), stdev = 0.231
  CI (99.9%): [3.488, 11.921] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.746 ops/ms
# Warmup Iteration   2: 5.375 ops/ms
# Warmup Iteration   3: 5.734 ops/ms
Iteration   1: 5.947 ops/ms
Iteration   2: 5.879 ops/ms
Iteration   3: 5.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.919 ±(99.9%) 0.656 ops/ms [Average]
  (min, avg, max) = (5.879, 5.919, 5.947), stdev = 0.036
  CI (99.9%): [5.263, 6.576] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.357 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.319 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.160 ±(99.9%) 0.010 ms/op
Iteration   1: 4.083 ±(99.9%) 0.003 ms/op
Iteration   2: 3.955 ±(99.9%) 0.003 ms/op
Iteration   3: 4.104 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.047 ±(99.9%) 1.470 ms/op [Average]
  (min, avg, max) = (3.955, 4.047, 4.104), stdev = 0.081
  CI (99.9%): [2.577, 5.517] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.968 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.009 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.004 ms/op
Iteration   1: 3.821 ±(99.9%) 0.003 ms/op
Iteration   2: 3.674 ±(99.9%) 0.003 ms/op
Iteration   3: 3.930 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.808 ±(99.9%) 2.349 ms/op [Average]
  (min, avg, max) = (3.674, 3.808, 3.930), stdev = 0.129
  CI (99.9%): [1.460, 6.157] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.083 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.005 ms/op
Iteration   1: 4.076 ±(99.9%) 0.003 ms/op
Iteration   2: 4.151 ±(99.9%) 0.006 ms/op
Iteration   3: 4.171 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.133 ±(99.9%) 0.912 ms/op [Average]
  (min, avg, max) = (4.076, 4.133, 4.171), stdev = 0.050
  CI (99.9%): [3.221, 5.044] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.313 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.810 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.455 ±(99.9%) 0.020 ms/op
Iteration   1: 5.477 ±(99.9%) 0.023 ms/op
Iteration   2: 5.630 ±(99.9%) 0.026 ms/op
Iteration   3: 5.646 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.584 ±(99.9%) 1.700 ms/op [Average]
  (min, avg, max) = (5.477, 5.584, 5.646), stdev = 0.093
  CI (99.9%): [3.884, 7.284] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.968 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.584 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.349 ±(99.9%) 0.014 ms/op
Iteration   1: 4.148 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   3.977 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.898 ms/op
                 createUser·p0.99:   8.602 ms/op
                 createUser·p0.999:  14.380 ms/op
                 createUser·p0.9999: 18.818 ms/op
                 createUser·p1.00:   19.038 ms/op

Iteration   2: 4.187 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   4.002 ms/op
                 createUser·p0.90:   5.341 ms/op
                 createUser·p0.95:   5.931 ms/op
                 createUser·p0.99:   8.241 ms/op
                 createUser·p0.999:  13.441 ms/op
                 createUser·p0.9999: 24.862 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   3: 4.300 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.609 ms/op
                 createUser·p0.50:   4.157 ms/op
                 createUser·p0.90:   5.300 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   7.864 ms/op
                 createUser·p0.999:  14.783 ms/op
                 createUser·p0.9999: 26.182 ms/op
                 createUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 227933
  mean =      4.211 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4909 
    [ 2.500,  5.000) = 188972 
    [ 5.000,  7.500) = 30590 
    [ 7.500, 10.000) = 2453 
    [10.000, 12.500) = 574 
    [12.500, 15.000) = 256 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.609 ms/op
     p(50.0000) =      4.043 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     24.983 ms/op
     p(99.9990) =     26.393 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.772 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.325 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.971 ±(99.9%) 0.011 ms/op
Iteration   1: 3.963 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.004 ms/op
                 existUser·p0.50:   3.838 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  13.012 ms/op
                 existUser·p0.9999: 15.613 ms/op
                 existUser·p1.00:   16.155 ms/op

Iteration   2: 3.876 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.850 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   6.881 ms/op
                 existUser·p0.999:  12.532 ms/op
                 existUser·p0.9999: 21.406 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   3: 4.014 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   3.867 ms/op
                 existUser·p0.90:   4.981 ms/op
                 existUser·p0.95:   5.497 ms/op
                 existUser·p0.99:   7.356 ms/op
                 existUser·p0.999:  10.830 ms/op
                 existUser·p0.9999: 19.629 ms/op
                 existUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 242991
  mean =      3.950 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6416 
    [ 2.500,  5.000) = 213755 
    [ 5.000,  7.500) = 20954 
    [ 7.500, 10.000) = 1471 
    [10.000, 12.500) = 181 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.916 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     11.764 ms/op
     p(99.9900) =     20.339 ms/op
     p(99.9990) =     23.729 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.468 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.496 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.255 ±(99.9%) 0.014 ms/op
Iteration   1: 4.319 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   4.178 ms/op
                 getUser·p0.90:   5.448 ms/op
                 getUser·p0.95:   6.038 ms/op
                 getUser·p0.99:   8.069 ms/op
                 getUser·p0.999:  14.527 ms/op
                 getUser·p0.9999: 15.626 ms/op
                 getUser·p1.00:   15.942 ms/op

Iteration   2: 4.186 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   4.039 ms/op
                 getUser·p0.90:   5.210 ms/op
                 getUser·p0.95:   5.792 ms/op
                 getUser·p0.99:   8.036 ms/op
                 getUser·p0.999:  11.194 ms/op
                 getUser·p0.9999: 30.638 ms/op
                 getUser·p1.00:   32.145 ms/op

Iteration   3: 4.291 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   4.141 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.931 ms/op
                 getUser·p0.99:   7.984 ms/op
                 getUser·p0.999:  11.699 ms/op
                 getUser·p0.9999: 32.803 ms/op
                 getUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 225261
  mean =      4.265 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5086 
    [ 2.500,  5.000) = 183190 
    [ 5.000,  7.500) = 33844 
    [ 7.500, 10.000) = 2475 
    [10.000, 12.500) = 472 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      8.028 ms/op
     p(99.9000) =     11.682 ms/op
     p(99.9900) =     32.145 ms/op
     p(99.9990) =     33.030 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


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
# Warmup Iteration   1: 7.463 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 6.179 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.622 ±(99.9%) 0.022 ms/op
Iteration   1: 5.496 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.815 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   7.217 ms/op
                 listUser·p0.95:   8.159 ms/op
                 listUser·p0.99:   10.240 ms/op
                 listUser·p0.999:  15.817 ms/op
                 listUser·p0.9999: 18.388 ms/op
                 listUser·p1.00:   21.299 ms/op

Iteration   2: 6.725 ±(99.9%) 0.229 ms/op
                 listUser·p0.00:   1.659 ms/op
                 listUser·p0.50:   4.989 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   47.491 ms/op
                 listUser·p0.999:  240.738 ms/op
                 listUser·p0.9999: 362.283 ms/op
                 listUser·p1.00:   362.283 ms/op

Iteration   3: 9.010 ±(99.9%) 0.347 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   5.399 ms/op
                 listUser·p0.90:   8.634 ms/op
                 listUser·p0.95:   11.272 ms/op
                 listUser·p0.99:   131.338 ms/op
                 listUser·p0.999:  202.899 ms/op
                 listUser·p0.9999: 254.859 ms/op
                 listUser·p1.00:   266.600 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 142035
  mean =      6.791 ±(99.9%) 0.117 ms/op

  Histogram, ms/op:
    [  0.000,  25.000) = 140310 
    [ 25.000,  50.000) = 272 
    [ 50.000,  75.000) = 336 
    [ 75.000, 100.000) = 243 
    [100.000, 125.000) = 215 
    [125.000, 150.000) = 238 
    [150.000, 175.000) = 167 
    [175.000, 200.000) = 141 
    [200.000, 225.000) = 55 
    [225.000, 250.000) = 8 
    [250.000, 275.000) = 25 
    [275.000, 300.000) = 3 
    [300.000, 325.000) = 2 
    [325.000, 350.000) = 6 
    [350.000, 375.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      7.610 ms/op
     p(95.0000) =      8.897 ms/op
     p(99.0000) =     52.209 ms/op
     p(99.9000) =    193.453 ms/op
     p(99.9900) =    350.924 ms/op
     p(99.9990) =    362.283 ms/op
     p(99.9999) =    362.283 ms/op
    p(100.0000) =    362.283 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt    Score   Error   Units
ClientGrpc.createUser                      thrpt       3    7.852 ± 1.811  ops/ms
ClientGrpc.existUser                       thrpt       3    8.354 ± 1.221  ops/ms
ClientGrpc.getUser                         thrpt       3    7.705 ± 4.216  ops/ms
ClientGrpc.listUser                        thrpt       3    5.919 ± 0.656  ops/ms
ClientGrpc.createUser                       avgt       3    4.047 ± 1.470   ms/op
ClientGrpc.existUser                        avgt       3    3.808 ± 2.349   ms/op
ClientGrpc.getUser                          avgt       3    4.133 ± 0.912   ms/op
ClientGrpc.listUser                         avgt       3    5.584 ± 1.700   ms/op
ClientGrpc.createUser                     sample  227933    4.211 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample            0.609           ms/op
ClientGrpc.createUser:createUser·p0.50    sample            4.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample            5.300           ms/op
ClientGrpc.createUser:createUser·p0.95    sample            5.874           ms/op
ClientGrpc.createUser:createUser·p0.99    sample            8.241           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           14.189           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample           24.983           ms/op
ClientGrpc.createUser:createUser·p1.00    sample           26.542           ms/op
ClientGrpc.existUser                      sample  242991    3.950 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample            0.916           ms/op
ClientGrpc.existUser:existUser·p0.50      sample            3.817           ms/op
ClientGrpc.existUser:existUser·p0.90      sample            4.956           ms/op
ClientGrpc.existUser:existUser·p0.95      sample            5.472           ms/op
ClientGrpc.existUser:existUser·p0.99      sample            7.168           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           11.764           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample           20.339           ms/op
ClientGrpc.existUser:existUser·p1.00      sample           23.855           ms/op
ClientGrpc.getUser                        sample  225261    4.265 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample            1.002           ms/op
ClientGrpc.getUser:getUser·p0.50          sample            4.116           ms/op
ClientGrpc.getUser:getUser·p0.90          sample            5.366           ms/op
ClientGrpc.getUser:getUser·p0.95          sample            5.931           ms/op
ClientGrpc.getUser:getUser·p0.99          sample            8.028           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           11.682           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample           32.145           ms/op
ClientGrpc.getUser:getUser·p1.00          sample           33.063           ms/op
ClientGrpc.listUser                       sample  142035    6.791 ± 0.117   ms/op
ClientGrpc.listUser:listUser·p0.00        sample            1.391           ms/op
ClientGrpc.listUser:listUser·p0.50        sample            5.177           ms/op
ClientGrpc.listUser:listUser·p0.90        sample            7.610           ms/op
ClientGrpc.listUser:listUser·p0.95        sample            8.897           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           52.209           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          193.453           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          350.924           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          362.283           ms/op
