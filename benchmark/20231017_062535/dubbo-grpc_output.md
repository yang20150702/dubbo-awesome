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
# Warmup Iteration   1: 1.769 ops/ms
# Warmup Iteration   2: 4.639 ops/ms
# Warmup Iteration   3: 6.784 ops/ms
Iteration   1: 7.026 ops/ms
Iteration   2: 6.842 ops/ms
Iteration   3: 7.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.958 ±(99.9%) 1.845 ops/ms [Average]
  (min, avg, max) = (6.842, 6.958, 7.026), stdev = 0.101
  CI (99.9%): [5.113, 8.803] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.107 ops/ms
# Warmup Iteration   2: 6.653 ops/ms
# Warmup Iteration   3: 7.167 ops/ms
Iteration   1: 7.674 ops/ms
Iteration   2: 7.777 ops/ms
Iteration   3: 7.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.752 ±(99.9%) 1.249 ops/ms [Average]
  (min, avg, max) = (7.674, 7.752, 7.804), stdev = 0.068
  CI (99.9%): [6.502, 9.001] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.959 ops/ms
# Warmup Iteration   2: 6.713 ops/ms
# Warmup Iteration   3: 7.266 ops/ms
Iteration   1: 7.340 ops/ms
Iteration   2: 7.736 ops/ms
Iteration   3: 7.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.542 ±(99.9%) 3.617 ops/ms [Average]
  (min, avg, max) = (7.340, 7.542, 7.736), stdev = 0.198
  CI (99.9%): [3.925, 11.159] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.757 ops/ms
# Warmup Iteration   2: 5.462 ops/ms
# Warmup Iteration   3: 5.810 ops/ms
Iteration   1: 5.885 ops/ms
Iteration   2: 5.802 ops/ms
Iteration   3: 6.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.909 ±(99.9%) 2.193 ops/ms [Average]
  (min, avg, max) = (5.802, 5.909, 6.039), stdev = 0.120
  CI (99.9%): [3.716, 8.101] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.706 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 4.833 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.585 ±(99.9%) 0.014 ms/op
Iteration   1: 4.549 ±(99.9%) 0.003 ms/op
Iteration   2: 4.554 ±(99.9%) 0.003 ms/op
Iteration   3: 4.438 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.514 ±(99.9%) 1.195 ms/op [Average]
  (min, avg, max) = (4.438, 4.514, 4.554), stdev = 0.066
  CI (99.9%): [3.318, 5.709] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.635 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.554 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.321 ±(99.9%) 0.007 ms/op
Iteration   1: 4.069 ±(99.9%) 0.003 ms/op
Iteration   2: 4.050 ±(99.9%) 0.003 ms/op
Iteration   3: 4.152 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.090 ±(99.9%) 0.993 ms/op [Average]
  (min, avg, max) = (4.050, 4.090, 4.152), stdev = 0.054
  CI (99.9%): [3.097, 5.084] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.523 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.307 ±(99.9%) 0.004 ms/op
Iteration   1: 4.171 ±(99.9%) 0.003 ms/op
Iteration   2: 4.304 ±(99.9%) 0.002 ms/op
Iteration   3: 4.201 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.225 ±(99.9%) 1.273 ms/op [Average]
  (min, avg, max) = (4.171, 4.225, 4.304), stdev = 0.070
  CI (99.9%): [2.952, 5.498] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.803 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 5.812 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.392 ±(99.9%) 0.019 ms/op
Iteration   1: 5.477 ±(99.9%) 0.013 ms/op
Iteration   2: 5.419 ±(99.9%) 0.017 ms/op
Iteration   3: 5.564 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.487 ±(99.9%) 1.333 ms/op [Average]
  (min, avg, max) = (5.419, 5.487, 5.564), stdev = 0.073
  CI (99.9%): [4.153, 6.820] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.280 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.715 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.013 ms/op
Iteration   1: 4.287 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.085 ms/op
                 createUser·p0.50:   4.133 ms/op
                 createUser·p0.90:   5.390 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   8.684 ms/op
                 createUser·p0.999:  15.209 ms/op
                 createUser·p0.9999: 18.711 ms/op
                 createUser·p1.00:   19.235 ms/op

Iteration   2: 4.340 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   4.170 ms/op
                 createUser·p0.90:   5.595 ms/op
                 createUser·p0.95:   6.144 ms/op
                 createUser·p0.99:   8.061 ms/op
                 createUser·p0.999:  17.606 ms/op
                 createUser·p0.9999: 27.927 ms/op
                 createUser·p1.00:   28.639 ms/op

Iteration   3: 4.171 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.165 ms/op
                 createUser·p0.50:   4.030 ms/op
                 createUser·p0.90:   5.325 ms/op
                 createUser·p0.95:   5.857 ms/op
                 createUser·p0.99:   7.700 ms/op
                 createUser·p0.999:  13.127 ms/op
                 createUser·p0.9999: 24.193 ms/op
                 createUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 225149
  mean =      4.265 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5367 
    [ 2.500,  5.000) = 180497 
    [ 5.000,  7.500) = 35958 
    [ 7.500, 10.000) = 2518 
    [10.000, 12.500) = 418 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      6.013 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     15.494 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     28.598 ms/op
     p(99.9999) =     28.639 ms/op
    p(100.0000) =     28.639 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.186 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.336 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.011 ms/op
Iteration   1: 4.015 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.437 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   5.087 ms/op
                 existUser·p0.95:   5.603 ms/op
                 existUser·p0.99:   7.791 ms/op
                 existUser·p0.999:  12.316 ms/op
                 existUser·p0.9999: 19.469 ms/op
                 existUser·p1.00:   20.185 ms/op

Iteration   2: 3.943 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.546 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  10.811 ms/op
                 existUser·p0.9999: 18.798 ms/op
                 existUser·p1.00:   19.137 ms/op

Iteration   3: 3.937 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.948 ms/op
                 existUser·p0.95:   5.439 ms/op
                 existUser·p0.99:   7.547 ms/op
                 existUser·p0.999:  10.318 ms/op
                 existUser·p0.9999: 23.163 ms/op
                 existUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 242007
  mean =      3.965 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6676 
    [ 2.500,  5.000) = 210275 
    [ 5.000,  7.500) = 22602 
    [ 7.500, 10.000) = 2031 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.437 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      5.022 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     10.879 ms/op
     p(99.9900) =     22.446 ms/op
     p(99.9990) =     23.729 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.178 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.467 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.292 ±(99.9%) 0.013 ms/op
Iteration   1: 4.179 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   4.035 ms/op
                 getUser·p0.90:   5.259 ms/op
                 getUser·p0.95:   5.800 ms/op
                 getUser·p0.99:   7.881 ms/op
                 getUser·p0.999:  11.977 ms/op
                 getUser·p0.9999: 14.626 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   2: 4.195 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   4.067 ms/op
                 getUser·p0.90:   5.308 ms/op
                 getUser·p0.95:   5.816 ms/op
                 getUser·p0.99:   7.332 ms/op
                 getUser·p0.999:  10.904 ms/op
                 getUser·p0.9999: 19.645 ms/op
                 getUser·p1.00:   19.857 ms/op

Iteration   3: 4.191 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.870 ms/op
                 getUser·p0.50:   4.080 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.677 ms/op
                 getUser·p0.99:   7.496 ms/op
                 getUser·p0.999:  13.574 ms/op
                 getUser·p0.9999: 25.199 ms/op
                 getUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 229146
  mean =      4.188 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3880 
    [ 2.500,  5.000) = 191330 
    [ 5.000,  7.500) = 31513 
    [ 7.500, 10.000) = 1917 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      4.059 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     11.960 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     25.255 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.266 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 6.044 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.418 ±(99.9%) 0.020 ms/op
Iteration   1: 5.266 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.446 ms/op
                 listUser·p0.50:   5.038 ms/op
                 listUser·p0.90:   6.808 ms/op
                 listUser·p0.95:   7.745 ms/op
                 listUser·p0.99:   10.191 ms/op
                 listUser·p0.999:  16.400 ms/op
                 listUser·p0.9999: 18.804 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   2: 5.370 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   5.128 ms/op
                 listUser·p0.90:   6.906 ms/op
                 listUser·p0.95:   7.782 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  18.547 ms/op
                 listUser·p0.9999: 20.519 ms/op
                 listUser·p1.00:   21.922 ms/op

Iteration   3: 5.296 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   5.063 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   7.717 ms/op
                 listUser·p0.99:   10.671 ms/op
                 listUser·p0.999:  18.895 ms/op
                 listUser·p0.9999: 22.815 ms/op
                 listUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180714
  mean =      5.310 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 141 
    [ 2.500,  5.000) = 84199 
    [ 5.000,  7.500) = 85564 
    [ 7.500, 10.000) = 8813 
    [10.000, 12.500) = 1470 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 170 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      5.079 ms/op
     p(90.0000) =      6.824 ms/op
     p(95.0000) =      7.750 ms/op
     p(99.0000) =     10.158 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     20.929 ms/op
     p(99.9990) =     23.815 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.958 ± 1.845  ops/ms
ClientGrpc.existUser                       thrpt       3   7.752 ± 1.249  ops/ms
ClientGrpc.getUser                         thrpt       3   7.542 ± 3.617  ops/ms
ClientGrpc.listUser                        thrpt       3   5.909 ± 2.193  ops/ms
ClientGrpc.createUser                       avgt       3   4.514 ± 1.195   ms/op
ClientGrpc.existUser                        avgt       3   4.090 ± 0.993   ms/op
ClientGrpc.getUser                          avgt       3   4.225 ± 1.273   ms/op
ClientGrpc.listUser                         avgt       3   5.487 ± 1.333   ms/op
ClientGrpc.createUser                     sample  225149   4.265 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.085           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.112           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.439           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.013           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.143           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.494           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.084           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.639           ms/op
ClientGrpc.existUser                      sample  242007   3.965 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.437           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.830           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.022           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.530           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.520           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.879           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.446           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.855           ms/op
ClientGrpc.getUser                        sample  229146   4.188 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.870           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.059           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.267           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.759           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.594           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.960           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.969           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.264           ms/op
ClientGrpc.listUser                       sample  180714   5.310 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.405           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.750           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.158           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.121           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.929           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.921           ms/op
