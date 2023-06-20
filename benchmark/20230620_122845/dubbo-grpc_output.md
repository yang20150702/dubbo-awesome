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
# Warmup Iteration   1: 2.339 ops/ms
# Warmup Iteration   2: 5.345 ops/ms
# Warmup Iteration   3: 6.714 ops/ms
Iteration   1: 6.810 ops/ms
Iteration   2: 7.172 ops/ms
Iteration   3: 7.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.138 ±(99.9%) 5.706 ops/ms [Average]
  (min, avg, max) = (6.810, 7.138, 7.433), stdev = 0.313
  CI (99.9%): [1.432, 12.844] (assumes normal distribution)


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
# Warmup Iteration   1: 4.992 ops/ms
# Warmup Iteration   2: 7.033 ops/ms
# Warmup Iteration   3: 7.565 ops/ms
Iteration   1: 7.852 ops/ms
Iteration   2: 7.975 ops/ms
Iteration   3: 7.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.939 ±(99.9%) 1.384 ops/ms [Average]
  (min, avg, max) = (7.852, 7.939, 7.991), stdev = 0.076
  CI (99.9%): [6.555, 9.323] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.373 ops/ms
# Warmup Iteration   2: 6.813 ops/ms
# Warmup Iteration   3: 7.224 ops/ms
Iteration   1: 6.997 ops/ms
Iteration   2: 7.341 ops/ms
Iteration   3: 7.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.168 ±(99.9%) 3.139 ops/ms [Average]
  (min, avg, max) = (6.997, 7.168, 7.341), stdev = 0.172
  CI (99.9%): [4.029, 10.307] (assumes normal distribution)


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
# Warmup Iteration   1: 3.627 ops/ms
# Warmup Iteration   2: 5.499 ops/ms
# Warmup Iteration   3: 5.837 ops/ms
Iteration   1: 5.671 ops/ms
Iteration   2: 5.863 ops/ms
Iteration   3: 5.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.831 ±(99.9%) 2.662 ops/ms [Average]
  (min, avg, max) = (5.671, 5.831, 5.958), stdev = 0.146
  CI (99.9%): [3.168, 8.493] (assumes normal distribution)


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
# Warmup Iteration   1: 6.453 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.486 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.483 ±(99.9%) 0.007 ms/op
Iteration   1: 4.341 ±(99.9%) 0.003 ms/op
Iteration   2: 4.332 ±(99.9%) 0.003 ms/op
Iteration   3: 4.319 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.331 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (4.319, 4.331, 4.341), stdev = 0.011
  CI (99.9%): [4.123, 4.538] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.339 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.134 ±(99.9%) 0.003 ms/op
Iteration   1: 4.078 ±(99.9%) 0.002 ms/op
Iteration   2: 4.124 ±(99.9%) 0.004 ms/op
Iteration   3: 4.195 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.132 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (4.078, 4.132, 4.195), stdev = 0.059
  CI (99.9%): [3.053, 5.212] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.207 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.648 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.526 ±(99.9%) 0.022 ms/op
Iteration   1: 4.247 ±(99.9%) 0.007 ms/op
Iteration   2: 4.307 ±(99.9%) 0.005 ms/op
Iteration   3: 4.285 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.280 ±(99.9%) 0.558 ms/op [Average]
  (min, avg, max) = (4.247, 4.280, 4.307), stdev = 0.031
  CI (99.9%): [3.721, 4.838] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.128 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.799 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.322 ±(99.9%) 0.014 ms/op
Iteration   1: 5.410 ±(99.9%) 0.009 ms/op
Iteration   2: 5.268 ±(99.9%) 0.008 ms/op
Iteration   3: 5.264 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.314 ±(99.9%) 1.515 ms/op [Average]
  (min, avg, max) = (5.264, 5.314, 5.410), stdev = 0.083
  CI (99.9%): [3.799, 6.829] (assumes normal distribution)


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
# Warmup Iteration   1: 6.713 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.636 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.012 ms/op
Iteration   1: 4.216 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.139 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.292 ms/op
                 createUser·p0.95:   5.743 ms/op
                 createUser·p0.99:   7.053 ms/op
                 createUser·p0.999:  12.013 ms/op
                 createUser·p0.9999: 16.771 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   2: 4.233 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  13.737 ms/op
                 createUser·p0.9999: 17.655 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   3: 4.217 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   4.137 ms/op
                 createUser·p0.90:   5.284 ms/op
                 createUser·p0.95:   5.692 ms/op
                 createUser·p0.99:   7.021 ms/op
                 createUser·p0.999:  11.657 ms/op
                 createUser·p0.9999: 19.740 ms/op
                 createUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 227270
  mean =      4.222 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3861 
    [ 2.500,  5.000) = 187792 
    [ 5.000,  7.500) = 33835 
    [ 7.500, 10.000) = 1303 
    [10.000, 12.500) = 284 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     11.928 ms/op
     p(99.9900) =     18.153 ms/op
     p(99.9990) =     19.994 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 5.716 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.011 ms/op
Iteration   1: 3.899 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.284 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  8.880 ms/op
                 existUser·p0.9999: 13.084 ms/op
                 existUser·p1.00:   13.484 ms/op

Iteration   2: 3.931 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   3.826 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.259 ms/op
                 existUser·p0.99:   6.910 ms/op
                 existUser·p0.999:  12.747 ms/op
                 existUser·p0.9999: 18.280 ms/op
                 existUser·p1.00:   19.988 ms/op

Iteration   3: 3.993 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   3.903 ms/op
                 existUser·p0.90:   4.923 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   6.578 ms/op
                 existUser·p0.999:  14.243 ms/op
                 existUser·p0.9999: 20.086 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 243549
  mean =      3.941 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5555 
    [ 2.500,  5.000) = 218061 
    [ 5.000,  7.500) = 18542 
    [ 7.500, 10.000) = 988 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     12.066 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     20.423 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 6.974 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.714 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.441 ±(99.9%) 0.014 ms/op
Iteration   1: 4.536 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.994 ms/op
                 getUser·p0.50:   4.375 ms/op
                 getUser·p0.90:   5.808 ms/op
                 getUser·p0.95:   6.332 ms/op
                 getUser·p0.99:   8.298 ms/op
                 getUser·p0.999:  17.548 ms/op
                 getUser·p0.9999: 24.114 ms/op
                 getUser·p1.00:   24.609 ms/op

Iteration   2: 4.339 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   4.260 ms/op
                 getUser·p0.90:   5.489 ms/op
                 getUser·p0.95:   5.898 ms/op
                 getUser·p0.99:   7.062 ms/op
                 getUser·p0.999:  11.277 ms/op
                 getUser·p0.9999: 21.398 ms/op
                 getUser·p1.00:   22.086 ms/op

Iteration   3: 4.298 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   4.202 ms/op
                 getUser·p0.90:   5.317 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  9.625 ms/op
                 getUser·p0.9999: 26.021 ms/op
                 getUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218706
  mean =      4.388 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5266 
    [ 2.500,  5.000) = 167326 
    [ 5.000,  7.500) = 43909 
    [ 7.500, 10.000) = 1704 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.985 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.538 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     12.255 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     26.470 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.036 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 6.018 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.611 ±(99.9%) 0.019 ms/op
Iteration   1: 5.504 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.524 ms/op
                 listUser·p0.50:   5.267 ms/op
                 listUser·p0.90:   7.086 ms/op
                 listUser·p0.95:   7.979 ms/op
                 listUser·p0.99:   10.191 ms/op
                 listUser·p0.999:  15.417 ms/op
                 listUser·p0.9999: 19.521 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   2: 5.429 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.573 ms/op
                 listUser·p0.50:   5.226 ms/op
                 listUser·p0.90:   6.840 ms/op
                 listUser·p0.95:   7.848 ms/op
                 listUser·p0.99:   10.157 ms/op
                 listUser·p0.999:  18.547 ms/op
                 listUser·p0.9999: 21.106 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   3: 5.413 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.729 ms/op
                 listUser·p0.50:   5.186 ms/op
                 listUser·p0.90:   6.922 ms/op
                 listUser·p0.95:   7.823 ms/op
                 listUser·p0.99:   10.109 ms/op
                 listUser·p0.999:  21.097 ms/op
                 listUser·p0.9999: 23.880 ms/op
                 listUser·p1.00:   24.969 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176161
  mean =      5.448 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 180 
    [ 2.500,  5.000) = 70223 
    [ 5.000,  7.500) = 94019 
    [ 7.500, 10.000) = 9790 
    [10.000, 12.500) = 1455 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.524 ms/op
     p(50.0000) =      5.226 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      7.889 ms/op
     p(99.0000) =     10.158 ms/op
     p(99.9000) =     18.602 ms/op
     p(99.9900) =     23.540 ms/op
     p(99.9990) =     24.520 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.138 ± 5.706  ops/ms
ClientGrpc.existUser                       thrpt       3   7.939 ± 1.384  ops/ms
ClientGrpc.getUser                         thrpt       3   7.168 ± 3.139  ops/ms
ClientGrpc.listUser                        thrpt       3   5.831 ± 2.662  ops/ms
ClientGrpc.createUser                       avgt       3   4.331 ± 0.207   ms/op
ClientGrpc.existUser                        avgt       3   4.132 ± 1.080   ms/op
ClientGrpc.getUser                          avgt       3   4.280 ± 0.558   ms/op
ClientGrpc.listUser                         avgt       3   5.314 ± 1.515   ms/op
ClientGrpc.createUser                     sample  227270   4.222 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.834           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.284           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.726           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.094           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.928           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.153           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.087           ms/op
ClientGrpc.existUser                      sample  243549   3.941 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.757           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.842           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.882           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.292           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.668           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.066           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.562           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.742           ms/op
ClientGrpc.getUser                        sample  218706   4.388 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.985           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.538           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.997           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.504           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.255           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.428           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.542           ms/op
ClientGrpc.listUser                       sample  176161   5.448 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.524           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.889           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.158           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.602           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.540           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.969           ms/op
