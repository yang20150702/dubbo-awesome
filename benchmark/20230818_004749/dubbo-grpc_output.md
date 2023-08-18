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
# Warmup Iteration   1: 3.228 ops/ms
# Warmup Iteration   2: 6.304 ops/ms
# Warmup Iteration   3: 7.825 ops/ms
Iteration   1: 8.260 ops/ms
Iteration   2: 8.275 ops/ms
Iteration   3: 8.541 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.359 ±(99.9%) 2.885 ops/ms [Average]
  (min, avg, max) = (8.260, 8.359, 8.541), stdev = 0.158
  CI (99.9%): [5.474, 11.243] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.635 ops/ms
# Warmup Iteration   2: 8.285 ops/ms
# Warmup Iteration   3: 8.697 ops/ms
Iteration   1: 8.915 ops/ms
Iteration   2: 8.696 ops/ms
Iteration   3: 8.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.818 ±(99.9%) 2.045 ops/ms [Average]
  (min, avg, max) = (8.696, 8.818, 8.915), stdev = 0.112
  CI (99.9%): [6.773, 10.864] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.089 ops/ms
# Warmup Iteration   2: 8.073 ops/ms
# Warmup Iteration   3: 8.425 ops/ms
Iteration   1: 8.348 ops/ms
Iteration   2: 8.606 ops/ms
Iteration   3: 8.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.462 ±(99.9%) 2.404 ops/ms [Average]
  (min, avg, max) = (8.348, 8.462, 8.606), stdev = 0.132
  CI (99.9%): [6.058, 10.866] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.980 ops/ms
# Warmup Iteration   2: 6.124 ops/ms
# Warmup Iteration   3: 6.465 ops/ms
Iteration   1: 6.482 ops/ms
Iteration   2: 6.471 ops/ms
Iteration   3: 6.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.520 ±(99.9%) 1.391 ops/ms [Average]
  (min, avg, max) = (6.471, 6.520, 6.608), stdev = 0.076
  CI (99.9%): [5.129, 7.911] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.402 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.987 ±(99.9%) 0.044 ms/op
Iteration   1: 3.881 ±(99.9%) 0.009 ms/op
Iteration   2: 3.878 ±(99.9%) 0.006 ms/op
Iteration   3: 3.881 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.880 ±(99.9%) 0.032 ms/op [Average]
  (min, avg, max) = (3.878, 3.880, 3.881), stdev = 0.002
  CI (99.9%): [3.848, 3.911] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.127 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.698 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.004 ms/op
Iteration   1: 3.574 ±(99.9%) 0.003 ms/op
Iteration   2: 3.617 ±(99.9%) 0.004 ms/op
Iteration   3: 3.560 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.583 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (3.560, 3.583, 3.617), stdev = 0.030
  CI (99.9%): [3.042, 4.125] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.280 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.937 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.004 ms/op
Iteration   1: 3.829 ±(99.9%) 0.004 ms/op
Iteration   2: 3.760 ±(99.9%) 0.015 ms/op
Iteration   3: 3.791 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.794 ±(99.9%) 0.631 ms/op [Average]
  (min, avg, max) = (3.760, 3.794, 3.829), stdev = 0.035
  CI (99.9%): [3.162, 4.425] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.202 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.087 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.920 ±(99.9%) 0.015 ms/op
Iteration   1: 4.959 ±(99.9%) 0.020 ms/op
Iteration   2: 4.928 ±(99.9%) 0.013 ms/op
Iteration   3: 4.810 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.899 ±(99.9%) 1.442 ms/op [Average]
  (min, avg, max) = (4.810, 4.899, 4.959), stdev = 0.079
  CI (99.9%): [3.457, 6.341] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.659 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.010 ms/op
Iteration   1: 3.726 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   6.035 ms/op
                 createUser·p0.999:  10.570 ms/op
                 createUser·p0.9999: 15.221 ms/op
                 createUser·p1.00:   15.565 ms/op

Iteration   2: 3.733 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  12.915 ms/op
                 createUser·p0.9999: 16.941 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   3: 3.777 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   5.910 ms/op
                 createUser·p0.999:  11.141 ms/op
                 createUser·p0.9999: 19.300 ms/op
                 createUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 256183
  mean =      3.745 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 105 
    [ 1.250,  2.500) = 10211 
    [ 2.500,  3.750) = 126573 
    [ 3.750,  5.000) = 110746 
    [ 5.000,  6.250) = 6667 
    [ 6.250,  7.500) = 881 
    [ 7.500,  8.750) = 405 
    [ 8.750, 10.000) = 194 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 74 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     11.518 ms/op
     p(99.9900) =     18.973 ms/op
     p(99.9990) =     19.558 ms/op
     p(99.9999) =     19.694 ms/op
    p(100.0000) =     19.694 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.028 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.657 ±(99.9%) 0.009 ms/op
Iteration   1: 3.597 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.043 ms/op
                 existUser·p0.50:   3.564 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  8.765 ms/op
                 existUser·p0.9999: 14.343 ms/op
                 existUser·p1.00:   14.959 ms/op

Iteration   2: 3.648 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  12.989 ms/op
                 existUser·p0.9999: 15.882 ms/op
                 existUser·p1.00:   17.400 ms/op

Iteration   3: 3.644 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  8.962 ms/op
                 existUser·p0.9999: 31.261 ms/op
                 existUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264419
  mean =      3.630 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6775 
    [ 2.500,  5.000) = 251420 
    [ 5.000,  7.500) = 5428 
    [ 7.500, 10.000) = 570 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     29.706 ms/op
     p(99.9990) =     31.382 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.316 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.009 ms/op
Iteration   1: 3.786 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   3.719 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   6.111 ms/op
                 getUser·p0.999:  11.356 ms/op
                 getUser·p0.9999: 22.413 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   2: 3.782 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   5.800 ms/op
                 getUser·p0.999:  8.782 ms/op
                 getUser·p0.9999: 14.722 ms/op
                 getUser·p1.00:   16.302 ms/op

Iteration   3: 3.736 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  9.067 ms/op
                 getUser·p0.9999: 20.196 ms/op
                 getUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 254787
  mean =      3.768 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9198 
    [ 2.500,  5.000) = 235795 
    [ 5.000,  7.500) = 8971 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =      9.473 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     23.136 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.265 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.422 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.996 ±(99.9%) 0.015 ms/op
Iteration   1: 4.948 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   4.743 ms/op
                 listUser·p0.90:   6.144 ms/op
                 listUser·p0.95:   7.029 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  15.941 ms/op
                 listUser·p0.9999: 20.124 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   2: 4.846 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.841 ms/op
                 listUser·p0.95:   7.053 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  17.337 ms/op
                 listUser·p0.9999: 21.791 ms/op
                 listUser·p1.00:   24.969 ms/op

Iteration   3: 4.900 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   5.898 ms/op
                 listUser·p0.95:   6.922 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  25.561 ms/op
                 listUser·p0.9999: 34.603 ms/op
                 listUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 195963
  mean =      4.898 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 193 
    [ 2.500,  5.000) = 137586 
    [ 5.000,  7.500) = 51612 
    [ 7.500, 10.000) = 5603 
    [10.000, 12.500) = 537 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 55 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      4.694 ms/op
     p(90.0000) =      5.980 ms/op
     p(95.0000) =      6.996 ms/op
     p(99.0000) =      8.749 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     34.040 ms/op
     p(99.9990) =     34.737 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.359 ± 2.885  ops/ms
ClientGrpc.existUser                       thrpt       3   8.818 ± 2.045  ops/ms
ClientGrpc.getUser                         thrpt       3   8.462 ± 2.404  ops/ms
ClientGrpc.listUser                        thrpt       3   6.520 ± 1.391  ops/ms
ClientGrpc.createUser                       avgt       3   3.880 ± 0.032   ms/op
ClientGrpc.existUser                        avgt       3   3.583 ± 0.541   ms/op
ClientGrpc.getUser                          avgt       3   3.794 ± 0.631   ms/op
ClientGrpc.listUser                         avgt       3   4.899 ± 1.442   ms/op
ClientGrpc.createUser                     sample  256183   3.745 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.878           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.784           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.964           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.518           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.973           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.694           ms/op
ClientGrpc.existUser                      sample  264419   3.630 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.904           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.833           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.634           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.706           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.178           ms/op
ClientGrpc.getUser                        sample  254787   3.768 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.728           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.997           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.473           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.185           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.331           ms/op
ClientGrpc.listUser                       sample  195963   4.898 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.106           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.694           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.980           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.749           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.007           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.040           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.800           ms/op
