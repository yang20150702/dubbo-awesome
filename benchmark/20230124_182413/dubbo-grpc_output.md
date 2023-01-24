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
# Warmup Iteration   1: 3.002 ops/ms
# Warmup Iteration   2: 6.751 ops/ms
# Warmup Iteration   3: 7.869 ops/ms
Iteration   1: 8.030 ops/ms
Iteration   2: 8.411 ops/ms
Iteration   3: 8.350 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.264 ±(99.9%) 3.730 ops/ms [Average]
  (min, avg, max) = (8.030, 8.264, 8.411), stdev = 0.204
  CI (99.9%): [4.534, 11.994] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.347 ops/ms
# Warmup Iteration   2: 8.104 ops/ms
# Warmup Iteration   3: 8.558 ops/ms
Iteration   1: 8.861 ops/ms
Iteration   2: 8.836 ops/ms
Iteration   3: 8.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.842 ±(99.9%) 0.299 ops/ms [Average]
  (min, avg, max) = (8.830, 8.842, 8.861), stdev = 0.016
  CI (99.9%): [8.543, 9.142] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.294 ops/ms
# Warmup Iteration   2: 7.820 ops/ms
# Warmup Iteration   3: 8.054 ops/ms
Iteration   1: 8.204 ops/ms
Iteration   2: 8.321 ops/ms
Iteration   3: 8.530 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.351 ±(99.9%) 3.012 ops/ms [Average]
  (min, avg, max) = (8.204, 8.351, 8.530), stdev = 0.165
  CI (99.9%): [5.340, 11.363] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.162 ops/ms
# Warmup Iteration   2: 6.140 ops/ms
# Warmup Iteration   3: 6.441 ops/ms
Iteration   1: 6.668 ops/ms
Iteration   2: 6.549 ops/ms
Iteration   3: 6.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.612 ±(99.9%) 1.086 ops/ms [Average]
  (min, avg, max) = (6.549, 6.612, 6.668), stdev = 0.060
  CI (99.9%): [5.526, 7.698] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.632 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.004 ms/op
Iteration   1: 3.815 ±(99.9%) 0.005 ms/op
Iteration   2: 3.952 ±(99.9%) 0.003 ms/op
Iteration   3: 4.037 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.935 ±(99.9%) 2.035 ms/op [Average]
  (min, avg, max) = (3.815, 3.935, 4.037), stdev = 0.112
  CI (99.9%): [1.899, 5.970] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.916 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.876 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.004 ms/op
Iteration   1: 3.471 ±(99.9%) 0.004 ms/op
Iteration   2: 3.535 ±(99.9%) 0.003 ms/op
Iteration   3: 3.583 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.530 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (3.471, 3.530, 3.583), stdev = 0.057
  CI (99.9%): [2.498, 4.561] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.455 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.004 ms/op
Iteration   1: 3.843 ±(99.9%) 0.003 ms/op
Iteration   2: 3.817 ±(99.9%) 0.002 ms/op
Iteration   3: 3.791 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.817 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (3.791, 3.817, 3.843), stdev = 0.026
  CI (99.9%): [3.340, 4.294] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.007 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 5.115 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.845 ±(99.9%) 0.011 ms/op
Iteration   1: 4.850 ±(99.9%) 0.010 ms/op
Iteration   2: 4.825 ±(99.9%) 0.009 ms/op
Iteration   3: 4.803 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.826 ±(99.9%) 0.431 ms/op [Average]
  (min, avg, max) = (4.803, 4.826, 4.850), stdev = 0.024
  CI (99.9%): [4.395, 5.257] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.596 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.787 ±(99.9%) 0.010 ms/op
Iteration   1: 3.731 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.956 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  10.306 ms/op
                 createUser·p0.9999: 23.570 ms/op
                 createUser·p1.00:   24.117 ms/op

Iteration   2: 3.782 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.513 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  10.798 ms/op
                 createUser·p0.9999: 23.447 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   3: 3.829 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  19.988 ms/op
                 createUser·p0.9999: 38.339 ms/op
                 createUser·p1.00:   38.797 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 253994
  mean =      3.780 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4800 
    [ 2.500,  5.000) = 240251 
    [ 5.000,  7.500) = 8104 
    [ 7.500, 10.000) = 525 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     10.830 ms/op
     p(99.9900) =     36.831 ms/op
     p(99.9990) =     38.631 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.796 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.885 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.690 ±(99.9%) 0.009 ms/op
Iteration   1: 3.667 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   3.633 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   4.858 ms/op
                 existUser·p0.99:   6.003 ms/op
                 existUser·p0.999:  10.322 ms/op
                 existUser·p0.9999: 23.686 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   2: 3.499 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.017 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.383 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  8.653 ms/op
                 existUser·p0.9999: 21.823 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   3: 3.600 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.535 ms/op
                 existUser·p0.90:   4.399 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   5.865 ms/op
                 existUser·p0.999:  16.417 ms/op
                 existUser·p0.9999: 21.856 ms/op
                 existUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267599
  mean =      3.587 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16714 
    [ 2.500,  5.000) = 244343 
    [ 5.000,  7.500) = 5585 
    [ 7.500, 10.000) = 581 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     11.541 ms/op
     p(99.9900) =     22.913 ms/op
     p(99.9990) =     25.515 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 5.201 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.011 ms/op
Iteration   1: 3.869 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.760 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  15.532 ms/op
                 getUser·p0.9999: 21.552 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   2: 3.907 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.866 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  11.391 ms/op
                 getUser·p0.9999: 26.804 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   3: 3.870 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.822 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  10.029 ms/op
                 getUser·p0.9999: 30.957 ms/op
                 getUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 247245
  mean =      3.882 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8461 
    [ 2.500,  5.000) = 224310 
    [ 5.000,  7.500) = 13195 
    [ 7.500, 10.000) = 928 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.799 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     11.518 ms/op
     p(99.9900) =     30.272 ms/op
     p(99.9990) =     31.164 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 5.821 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.196 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.891 ±(99.9%) 0.015 ms/op
Iteration   1: 4.817 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.659 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.152 ms/op
                 listUser·p0.95:   6.840 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  15.335 ms/op
                 listUser·p0.9999: 17.619 ms/op
                 listUser·p1.00:   18.055 ms/op

Iteration   2: 4.841 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  17.917 ms/op
                 listUser·p0.9999: 27.525 ms/op
                 listUser·p1.00:   27.951 ms/op

Iteration   3: 4.744 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   6.742 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  19.155 ms/op
                 listUser·p0.9999: 22.078 ms/op
                 listUser·p1.00:   30.802 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199952
  mean =      4.800 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 366 
    [ 2.500,  5.000) = 145315 
    [ 5.000,  7.500) = 49048 
    [ 7.500, 10.000) = 4354 
    [10.000, 12.500) = 433 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      6.054 ms/op
     p(95.0000) =      6.775 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     17.827 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     27.952 ms/op
     p(99.9999) =     30.802 ms/op
    p(100.0000) =     30.802 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.264 ± 3.730  ops/ms
ClientGrpc.existUser                       thrpt       3   8.842 ± 0.299  ops/ms
ClientGrpc.getUser                         thrpt       3   8.351 ± 3.012  ops/ms
ClientGrpc.listUser                        thrpt       3   6.612 ± 1.086  ops/ms
ClientGrpc.createUser                       avgt       3   3.935 ± 2.035   ms/op
ClientGrpc.existUser                        avgt       3   3.530 ± 1.031   ms/op
ClientGrpc.getUser                          avgt       3   3.817 ± 0.477   ms/op
ClientGrpc.listUser                         avgt       3   4.826 ± 0.431   ms/op
ClientGrpc.createUser                     sample  253994   3.780 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.513           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.857           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.830           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          36.831           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          38.797           ms/op
ClientGrpc.existUser                      sample  267599   3.587 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.751           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.694           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.693           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.541           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.913           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.116           ms/op
ClientGrpc.getUser                        sample  247245   3.882 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.799           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.071           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.373           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.518           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.272           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.293           ms/op
ClientGrpc.listUser                       sample  199952   4.800 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.176           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.700           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.827           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.001           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.802           ms/op
