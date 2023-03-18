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
# Warmup Iteration   1: 2.273 ops/ms
# Warmup Iteration   2: 5.617 ops/ms
# Warmup Iteration   3: 7.577 ops/ms
Iteration   1: 7.761 ops/ms
Iteration   2: 8.003 ops/ms
Iteration   3: 7.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.778 ±(99.9%) 3.972 ops/ms [Average]
  (min, avg, max) = (7.569, 7.778, 8.003), stdev = 0.218
  CI (99.9%): [3.805, 11.750] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.882 ops/ms
# Warmup Iteration   2: 7.530 ops/ms
# Warmup Iteration   3: 7.797 ops/ms
Iteration   1: 8.387 ops/ms
Iteration   2: 8.379 ops/ms
Iteration   3: 8.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.345 ±(99.9%) 1.214 ops/ms [Average]
  (min, avg, max) = (8.268, 8.345, 8.387), stdev = 0.067
  CI (99.9%): [7.131, 9.558] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.377 ops/ms
# Warmup Iteration   2: 7.027 ops/ms
# Warmup Iteration   3: 7.693 ops/ms
Iteration   1: 7.788 ops/ms
Iteration   2: 7.913 ops/ms
Iteration   3: 8.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.969 ±(99.9%) 3.907 ops/ms [Average]
  (min, avg, max) = (7.788, 7.969, 8.205), stdev = 0.214
  CI (99.9%): [4.062, 11.876] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.892 ops/ms
# Warmup Iteration   2: 5.509 ops/ms
# Warmup Iteration   3: 6.038 ops/ms
Iteration   1: 5.880 ops/ms
Iteration   2: 6.141 ops/ms
Iteration   3: 6.138 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.053 ±(99.9%) 2.730 ops/ms [Average]
  (min, avg, max) = (5.880, 6.053, 6.141), stdev = 0.150
  CI (99.9%): [3.323, 8.783] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.448 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.533 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.015 ms/op
Iteration   1: 4.121 ±(99.9%) 0.003 ms/op
Iteration   2: 4.179 ±(99.9%) 0.003 ms/op
Iteration   3: 4.099 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.133 ±(99.9%) 0.747 ms/op [Average]
  (min, avg, max) = (4.099, 4.133, 4.179), stdev = 0.041
  CI (99.9%): [3.386, 4.880] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.843 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.003 ms/op
Iteration   1: 3.785 ±(99.9%) 0.003 ms/op
Iteration   2: 3.851 ±(99.9%) 0.003 ms/op
Iteration   3: 3.905 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.847 ±(99.9%) 1.097 ms/op [Average]
  (min, avg, max) = (3.785, 3.847, 3.905), stdev = 0.060
  CI (99.9%): [2.750, 4.944] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.457 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.421 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.002 ms/op
Iteration   1: 4.026 ±(99.9%) 0.003 ms/op
Iteration   2: 3.980 ±(99.9%) 0.004 ms/op
Iteration   3: 4.089 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.031 ±(99.9%) 0.999 ms/op [Average]
  (min, avg, max) = (3.980, 4.031, 4.089), stdev = 0.055
  CI (99.9%): [3.032, 5.030] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.300 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.389 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.319 ±(99.9%) 0.017 ms/op
Iteration   1: 5.183 ±(99.9%) 0.015 ms/op
Iteration   2: 5.129 ±(99.9%) 0.015 ms/op
Iteration   3: 5.007 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.106 ±(99.9%) 1.647 ms/op [Average]
  (min, avg, max) = (5.007, 5.106, 5.183), stdev = 0.090
  CI (99.9%): [3.459, 6.754] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.377 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.549 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.012 ms/op
Iteration   1: 4.141 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   3.953 ms/op
                 createUser·p0.90:   5.325 ms/op
                 createUser·p0.95:   5.865 ms/op
                 createUser·p0.99:   8.454 ms/op
                 createUser·p0.999:  14.726 ms/op
                 createUser·p0.9999: 17.769 ms/op
                 createUser·p1.00:   19.726 ms/op

Iteration   2: 4.125 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   4.018 ms/op
                 createUser·p0.90:   5.161 ms/op
                 createUser·p0.95:   5.571 ms/op
                 createUser·p0.99:   7.135 ms/op
                 createUser·p0.999:  11.886 ms/op
                 createUser·p0.9999: 18.628 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   3: 4.086 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.214 ms/op
                 createUser·p0.50:   3.965 ms/op
                 createUser·p0.90:   5.046 ms/op
                 createUser·p0.95:   5.472 ms/op
                 createUser·p0.99:   6.889 ms/op
                 createUser·p0.999:  11.566 ms/op
                 createUser·p0.9999: 21.731 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 233125
  mean =      4.117 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4960 
    [ 2.500,  5.000) = 198098 
    [ 5.000,  7.500) = 27673 
    [ 7.500, 10.000) = 1718 
    [10.000, 12.500) = 408 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      3.977 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     13.267 ms/op
     p(99.9900) =     20.154 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.020 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.026 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.011 ms/op
Iteration   1: 3.784 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.006 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.153 ms/op
                 existUser·p0.99:   6.578 ms/op
                 existUser·p0.999:  12.716 ms/op
                 existUser·p0.9999: 14.797 ms/op
                 existUser·p1.00:   15.041 ms/op

Iteration   2: 3.792 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   4.981 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  13.691 ms/op
                 existUser·p0.9999: 20.007 ms/op
                 existUser·p1.00:   20.185 ms/op

Iteration   3: 3.765 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.571 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   7.365 ms/op
                 existUser·p0.999:  10.962 ms/op
                 existUser·p0.9999: 18.891 ms/op
                 existUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 253970
  mean =      3.780 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7042 
    [ 2.500,  5.000) = 233444 
    [ 5.000,  7.500) = 11746 
    [ 7.500, 10.000) = 1270 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 166 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     12.435 ms/op
     p(99.9900) =     19.058 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.932 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.415 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.013 ms/op
Iteration   1: 4.016 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   3.899 ms/op
                 getUser·p0.90:   5.038 ms/op
                 getUser·p0.95:   5.573 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  10.740 ms/op
                 getUser·p0.9999: 15.828 ms/op
                 getUser·p1.00:   16.171 ms/op

Iteration   2: 4.114 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   5.128 ms/op
                 getUser·p0.95:   5.571 ms/op
                 getUser·p0.99:   6.797 ms/op
                 getUser·p0.999:  13.067 ms/op
                 getUser·p0.9999: 19.799 ms/op
                 getUser·p1.00:   20.054 ms/op

Iteration   3: 4.033 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.016 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   5.022 ms/op
                 getUser·p0.95:   5.472 ms/op
                 getUser·p0.99:   7.381 ms/op
                 getUser·p0.999:  12.775 ms/op
                 getUser·p0.9999: 19.438 ms/op
                 getUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 236783
  mean =      4.054 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5414 
    [ 2.500,  5.000) = 205224 
    [ 5.000,  7.500) = 24384 
    [ 7.500, 10.000) = 1234 
    [10.000, 12.500) = 262 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     19.453 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 7.731 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.519 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.180 ±(99.9%) 0.018 ms/op
Iteration   1: 5.178 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   4.923 ms/op
                 listUser·p0.90:   6.619 ms/op
                 listUser·p0.95:   7.668 ms/op
                 listUser·p0.99:   10.060 ms/op
                 listUser·p0.999:  16.523 ms/op
                 listUser·p0.9999: 18.911 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   2: 5.236 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   4.964 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   7.548 ms/op
                 listUser·p0.99:   9.625 ms/op
                 listUser·p0.999:  20.049 ms/op
                 listUser·p0.9999: 22.246 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   3: 5.188 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   4.940 ms/op
                 listUser·p0.90:   6.644 ms/op
                 listUser·p0.95:   7.569 ms/op
                 listUser·p0.99:   9.585 ms/op
                 listUser·p0.999:  24.432 ms/op
                 listUser·p0.9999: 30.698 ms/op
                 listUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 184527
  mean =      5.201 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 232 
    [ 2.500,  5.000) = 97417 
    [ 5.000,  7.500) = 76982 
    [ 7.500, 10.000) = 8346 
    [10.000, 12.500) = 1036 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      4.948 ms/op
     p(90.0000) =      6.676 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =      9.748 ms/op
     p(99.9000) =     19.218 ms/op
     p(99.9900) =     28.890 ms/op
     p(99.9990) =     31.379 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.778 ± 3.972  ops/ms
ClientGrpc.existUser                       thrpt       3   8.345 ± 1.214  ops/ms
ClientGrpc.getUser                         thrpt       3   7.969 ± 3.907  ops/ms
ClientGrpc.listUser                        thrpt       3   6.053 ± 2.730  ops/ms
ClientGrpc.createUser                       avgt       3   4.133 ± 0.747   ms/op
ClientGrpc.existUser                        avgt       3   3.847 ± 1.097   ms/op
ClientGrpc.getUser                          avgt       3   4.031 ± 0.999   ms/op
ClientGrpc.listUser                         avgt       3   5.106 ± 1.647   ms/op
ClientGrpc.createUser                     sample  233125   4.117 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.972           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.169           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.652           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.561           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.267           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.154           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.151           ms/op
ClientGrpc.existUser                      sample  253970   3.780 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.839           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.620           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.038           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.758           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.435           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.058           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.185           ms/op
ClientGrpc.getUser                        sample  236783   4.054 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.807           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.932           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.063           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.538           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.078           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.730           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.453           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.054           ms/op
ClientGrpc.listUser                       sample  184527   5.201 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.130           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.586           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.748           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.218           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.890           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.490           ms/op
