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
# Warmup Iteration   1: 4.855 ops/ms
# Warmup Iteration   2: 9.421 ops/ms
# Warmup Iteration   3: 10.793 ops/ms
Iteration   1: 10.344 ops/ms
Iteration   2: 10.835 ops/ms
Iteration   3: 10.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.605 ±(99.9%) 4.507 ops/ms [Average]
  (min, avg, max) = (10.344, 10.605, 10.835), stdev = 0.247
  CI (99.9%): [6.098, 15.112] (assumes normal distribution)


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
# Warmup Iteration   1: 7.599 ops/ms
# Warmup Iteration   2: 10.769 ops/ms
# Warmup Iteration   3: 11.148 ops/ms
Iteration   1: 11.474 ops/ms
Iteration   2: 11.426 ops/ms
Iteration   3: 11.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.352 ±(99.9%) 3.127 ops/ms [Average]
  (min, avg, max) = (11.156, 11.352, 11.474), stdev = 0.171
  CI (99.9%): [8.225, 14.480] (assumes normal distribution)


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
# Warmup Iteration   1: 7.674 ops/ms
# Warmup Iteration   2: 10.633 ops/ms
# Warmup Iteration   3: 10.786 ops/ms
Iteration   1: 10.957 ops/ms
Iteration   2: 10.906 ops/ms
Iteration   3: 10.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.912 ±(99.9%) 0.753 ops/ms [Average]
  (min, avg, max) = (10.875, 10.912, 10.957), stdev = 0.041
  CI (99.9%): [10.159, 11.666] (assumes normal distribution)


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
# Warmup Iteration   1: 6.396 ops/ms
# Warmup Iteration   2: 8.034 ops/ms
# Warmup Iteration   3: 8.506 ops/ms
Iteration   1: 8.439 ops/ms
Iteration   2: 8.400 ops/ms
Iteration   3: 8.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.397 ±(99.9%) 0.810 ops/ms [Average]
  (min, avg, max) = (8.351, 8.397, 8.439), stdev = 0.044
  CI (99.9%): [7.587, 9.206] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.975 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.003 ms/op
Iteration   1: 2.902 ±(99.9%) 0.001 ms/op
Iteration   2: 2.945 ±(99.9%) 0.003 ms/op
Iteration   3: 2.949 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.932 ±(99.9%) 0.469 ms/op [Average]
  (min, avg, max) = (2.902, 2.932, 2.949), stdev = 0.026
  CI (99.9%): [2.463, 3.401] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.772 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.877 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.837 ±(99.9%) 0.003 ms/op
Iteration   1: 2.789 ±(99.9%) 0.003 ms/op
Iteration   2: 2.844 ±(99.9%) 0.003 ms/op
Iteration   3: 2.825 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.819 ±(99.9%) 0.507 ms/op [Average]
  (min, avg, max) = (2.789, 2.819, 2.844), stdev = 0.028
  CI (99.9%): [2.312, 3.326] (assumes normal distribution)


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
# Warmup Iteration   1: 3.485 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.002 ms/op
Iteration   1: 2.949 ±(99.9%) 0.002 ms/op
Iteration   2: 2.939 ±(99.9%) 0.002 ms/op
Iteration   3: 2.936 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.941 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (2.936, 2.941, 2.949), stdev = 0.007
  CI (99.9%): [2.814, 3.068] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.784 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.018 ms/op
Iteration   1: 3.822 ±(99.9%) 0.033 ms/op
Iteration   2: 3.793 ±(99.9%) 0.035 ms/op
Iteration   3: 3.805 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.807 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (3.793, 3.807, 3.822), stdev = 0.014
  CI (99.9%): [3.547, 4.067] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.144 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.007 ms/op
Iteration   1: 2.952 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.072 ms/op
                 createUser·p0.9999: 17.110 ms/op
                 createUser·p1.00:   17.531 ms/op

Iteration   2: 2.903 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   2.920 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.336 ms/op
                 createUser·p0.9999: 16.694 ms/op
                 createUser·p1.00:   18.448 ms/op

Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.649 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  9.226 ms/op
                 createUser·p0.9999: 17.836 ms/op
                 createUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325485
  mean =      2.948 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3461 
    [ 1.250,  2.500) = 31383 
    [ 2.500,  3.750) = 275741 
    [ 3.750,  5.000) = 13334 
    [ 5.000,  6.250) = 912 
    [ 6.250,  7.500) = 316 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 57 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.775 ms/op
     p(99.9900) =     17.203 ms/op
     p(99.9990) =     18.301 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 3.713 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.958 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.835 ±(99.9%) 0.005 ms/op
Iteration   1: 2.846 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.165 ms/op
                 existUser·p0.9999: 11.658 ms/op
                 existUser·p1.00:   11.846 ms/op

Iteration   2: 2.849 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.615 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.084 ms/op
                 existUser·p0.999:  10.095 ms/op
                 existUser·p0.9999: 12.710 ms/op
                 existUser·p1.00:   13.025 ms/op

Iteration   3: 2.820 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.482 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.465 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.733 ms/op
                 existUser·p0.9999: 22.795 ms/op
                 existUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338170
  mean =      2.838 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51076 
    [ 2.500,  5.000) = 286089 
    [ 5.000,  7.500) = 659 
    [ 7.500, 10.000) = 135 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.647 ms/op
     p(99.9900) =     12.972 ms/op
     p(99.9990) =     22.938 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 3.799 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.007 ms/op
Iteration   1: 2.969 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.135 ms/op
                 getUser·p0.9999: 13.009 ms/op
                 getUser·p1.00:   13.500 ms/op

Iteration   2: 2.984 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.550 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.427 ms/op
                 getUser·p0.999:  7.294 ms/op
                 getUser·p0.9999: 22.315 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   3: 2.986 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.562 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.304 ms/op
                 getUser·p0.9999: 25.166 ms/op
                 getUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321925
  mean =      2.980 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32175 
    [ 2.500,  5.000) = 287834 
    [ 5.000,  7.500) = 1629 
    [ 7.500, 10.000) = 97 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.250 ms/op
     p(99.9900) =     24.039 ms/op
     p(99.9990) =     25.454 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 5.474 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.011 ms/op
Iteration   1: 3.839 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.114 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  12.904 ms/op
                 listUser·p0.9999: 16.406 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   2: 3.867 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.825 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  16.890 ms/op
                 listUser·p0.9999: 23.575 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   3: 3.754 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  14.120 ms/op
                 listUser·p0.9999: 25.968 ms/op
                 listUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251317
  mean =      3.819 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7122 
    [ 2.500,  5.000) = 222019 
    [ 5.000,  7.500) = 20702 
    [ 7.500, 10.000) = 825 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     14.527 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     26.477 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.605 ± 4.507  ops/ms
ClientGrpc.existUser                       thrpt       3  11.352 ± 3.127  ops/ms
ClientGrpc.getUser                         thrpt       3  10.912 ± 0.753  ops/ms
ClientGrpc.listUser                        thrpt       3   8.397 ± 0.810  ops/ms
ClientGrpc.createUser                       avgt       3   2.932 ± 0.469   ms/op
ClientGrpc.existUser                        avgt       3   2.819 ± 0.507   ms/op
ClientGrpc.getUser                          avgt       3   2.941 ± 0.127   ms/op
ClientGrpc.listUser                         avgt       3   3.807 ± 0.260   ms/op
ClientGrpc.createUser                     sample  325485   2.948 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.649           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.941           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.478           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.775           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.203           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.448           ms/op
ClientGrpc.existUser                      sample  338170   2.838 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.482           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.826           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.647           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          12.972           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.069           ms/op
ClientGrpc.getUser                        sample  321925   2.980 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.550           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.250           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.039           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.919           ms/op
ClientGrpc.listUser                       sample  251317   3.819 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.825           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.662           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.527           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.068           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.049           ms/op
