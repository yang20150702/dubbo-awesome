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
# Warmup Iteration   1: 4.812 ops/ms
# Warmup Iteration   2: 9.357 ops/ms
# Warmup Iteration   3: 10.404 ops/ms
Iteration   1: 10.829 ops/ms
Iteration   2: 10.791 ops/ms
Iteration   3: 10.940 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.853 ±(99.9%) 1.418 ops/ms [Average]
  (min, avg, max) = (10.791, 10.853, 10.940), stdev = 0.078
  CI (99.9%): [9.436, 12.271] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.335 ops/ms
# Warmup Iteration   2: 11.243 ops/ms
# Warmup Iteration   3: 11.216 ops/ms
Iteration   1: 11.301 ops/ms
Iteration   2: 11.098 ops/ms
Iteration   3: 11.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.233 ±(99.9%) 2.140 ops/ms [Average]
  (min, avg, max) = (11.098, 11.233, 11.301), stdev = 0.117
  CI (99.9%): [9.093, 13.373] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.841 ops/ms
# Warmup Iteration   2: 10.272 ops/ms
# Warmup Iteration   3: 10.760 ops/ms
Iteration   1: 10.631 ops/ms
Iteration   2: 10.641 ops/ms
Iteration   3: 10.878 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.717 ±(99.9%) 2.551 ops/ms [Average]
  (min, avg, max) = (10.631, 10.717, 10.878), stdev = 0.140
  CI (99.9%): [8.166, 13.268] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.772 ops/ms
# Warmup Iteration   2: 8.084 ops/ms
# Warmup Iteration   3: 8.476 ops/ms
Iteration   1: 8.262 ops/ms
Iteration   2: 8.268 ops/ms
Iteration   3: 8.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.295 ±(99.9%) 0.947 ops/ms [Average]
  (min, avg, max) = (8.262, 8.295, 8.354), stdev = 0.052
  CI (99.9%): [7.348, 9.242] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.079 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.002 ms/op
Iteration   1: 3.014 ±(99.9%) 0.003 ms/op
Iteration   2: 3.026 ±(99.9%) 0.002 ms/op
Iteration   3: 3.026 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.022 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (3.014, 3.022, 3.026), stdev = 0.007
  CI (99.9%): [2.898, 3.146] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.672 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.909 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.771 ±(99.9%) 0.003 ms/op
Iteration   1: 2.855 ±(99.9%) 0.003 ms/op
Iteration   2: 2.831 ±(99.9%) 0.003 ms/op
Iteration   3: 2.820 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.836 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (2.820, 2.836, 2.855), stdev = 0.018
  CI (99.9%): [2.513, 3.158] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.881 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.002 ms/op
Iteration   1: 2.983 ±(99.9%) 0.003 ms/op
Iteration   2: 3.011 ±(99.9%) 0.003 ms/op
Iteration   3: 2.994 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.996 ±(99.9%) 0.252 ms/op [Average]
  (min, avg, max) = (2.983, 2.996, 3.011), stdev = 0.014
  CI (99.9%): [2.743, 3.248] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.789 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.024 ms/op
Iteration   1: 3.812 ±(99.9%) 0.007 ms/op
Iteration   2: 3.790 ±(99.9%) 0.011 ms/op
Iteration   3: 3.850 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.817 ±(99.9%) 0.561 ms/op [Average]
  (min, avg, max) = (3.790, 3.817, 3.850), stdev = 0.031
  CI (99.9%): [3.257, 4.378] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.728 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
Iteration   1: 2.961 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  8.196 ms/op
                 createUser·p0.9999: 15.882 ms/op
                 createUser·p1.00:   17.596 ms/op

Iteration   2: 2.984 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.331 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  12.567 ms/op
                 createUser·p0.9999: 23.396 ms/op
                 createUser·p1.00:   23.790 ms/op

Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  8.823 ms/op
                 createUser·p0.9999: 20.425 ms/op
                 createUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322219
  mean =      2.980 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28670 
    [ 2.500,  5.000) = 291841 
    [ 5.000,  7.500) = 1170 
    [ 7.500, 10.000) = 196 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.331 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =     10.439 ms/op
     p(99.9900) =     22.345 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.845 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.947 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.866 ±(99.9%) 0.006 ms/op
Iteration   1: 2.825 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.523 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  8.240 ms/op
                 existUser·p0.9999: 17.596 ms/op
                 existUser·p1.00:   17.727 ms/op

Iteration   2: 2.848 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.528 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  7.602 ms/op
                 existUser·p0.9999: 13.919 ms/op
                 existUser·p1.00:   14.205 ms/op

Iteration   3: 2.845 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.555 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.439 ms/op
                 existUser·p0.9999: 14.766 ms/op
                 existUser·p1.00:   15.106 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 338061
  mean =      2.839 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4650 
    [ 1.250,  2.500) = 47928 
    [ 2.500,  3.750) = 272879 
    [ 3.750,  5.000) = 11230 
    [ 5.000,  6.250) = 722 
    [ 6.250,  7.500) = 319 
    [ 7.500,  8.750) = 150 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.523 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.479 ms/op
     p(99.9900) =     15.053 ms/op
     p(99.9990) =     17.695 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.822 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.943 ms/op
                 getUser·p0.9999: 19.038 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.455 ms/op
                 getUser·p0.9999: 23.757 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   3: 3.018 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.463 ms/op
                 getUser·p0.9999: 27.281 ms/op
                 getUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318266
  mean =      3.018 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26838 
    [ 2.500,  5.000) = 289591 
    [ 5.000,  7.500) = 1463 
    [ 7.500, 10.000) = 169 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      7.700 ms/op
     p(99.9900) =     25.636 ms/op
     p(99.9990) =     27.454 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 5.122 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.971 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.012 ms/op
Iteration   1: 3.884 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.740 ms/op
                 listUser·p0.999:  12.195 ms/op
                 listUser·p0.9999: 18.579 ms/op
                 listUser·p1.00:   18.940 ms/op

Iteration   2: 3.831 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.508 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  16.044 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   3: 3.873 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.911 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  14.975 ms/op
                 listUser·p0.9999: 16.551 ms/op
                 listUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248774
  mean =      3.862 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 7163 
    [ 2.500,  3.750) = 125195 
    [ 3.750,  5.000) = 93234 
    [ 5.000,  6.250) = 18376 
    [ 6.250,  7.500) = 3523 
    [ 7.500,  8.750) = 573 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 78 
    [15.000, 16.250) = 140 
    [16.250, 17.500) = 60 
    [17.500, 18.750) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     15.061 ms/op
     p(99.9900) =     18.616 ms/op
     p(99.9990) =     19.268 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.853 ± 1.418  ops/ms
ClientGrpc.existUser                       thrpt       3  11.233 ± 2.140  ops/ms
ClientGrpc.getUser                         thrpt       3  10.717 ± 2.551  ops/ms
ClientGrpc.listUser                        thrpt       3   8.295 ± 0.947  ops/ms
ClientGrpc.createUser                       avgt       3   3.022 ± 0.124   ms/op
ClientGrpc.existUser                        avgt       3   2.836 ± 0.323   ms/op
ClientGrpc.getUser                          avgt       3   2.996 ± 0.252   ms/op
ClientGrpc.listUser                         avgt       3   3.817 ± 0.561   ms/op
ClientGrpc.createUser                     sample  322219   2.980 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.331           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.478           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.439           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.345           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.790           ms/op
ClientGrpc.existUser                      sample  338061   2.839 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.523           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.617           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.479           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.053           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.727           ms/op
ClientGrpc.getUser                        sample  318266   3.018 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.632           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.700           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.636           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.475           ms/op
ClientGrpc.listUser                       sample  248774   3.862 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.508           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.061           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.616           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.268           ms/op
