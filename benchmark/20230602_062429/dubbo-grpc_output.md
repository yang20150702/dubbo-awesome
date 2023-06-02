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
# Warmup Iteration   1: 4.391 ops/ms
# Warmup Iteration   2: 9.099 ops/ms
# Warmup Iteration   3: 10.148 ops/ms
Iteration   1: 10.607 ops/ms
Iteration   2: 10.762 ops/ms
Iteration   3: 10.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.664 ±(99.9%) 1.555 ops/ms [Average]
  (min, avg, max) = (10.607, 10.664, 10.762), stdev = 0.085
  CI (99.9%): [9.108, 12.219] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.850 ops/ms
# Warmup Iteration   2: 10.834 ops/ms
# Warmup Iteration   3: 11.317 ops/ms
Iteration   1: 11.456 ops/ms
Iteration   2: 11.455 ops/ms
Iteration   3: 11.282 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.398 ±(99.9%) 1.827 ops/ms [Average]
  (min, avg, max) = (11.282, 11.398, 11.456), stdev = 0.100
  CI (99.9%): [9.571, 13.224] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.224 ops/ms
# Warmup Iteration   2: 10.258 ops/ms
# Warmup Iteration   3: 10.748 ops/ms
Iteration   1: 10.820 ops/ms
Iteration   2: 10.874 ops/ms
Iteration   3: 10.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.798 ±(99.9%) 1.615 ops/ms [Average]
  (min, avg, max) = (10.701, 10.798, 10.874), stdev = 0.089
  CI (99.9%): [9.183, 12.413] (assumes normal distribution)


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
# Warmup Iteration   1: 6.076 ops/ms
# Warmup Iteration   2: 7.813 ops/ms
# Warmup Iteration   3: 8.141 ops/ms
Iteration   1: 8.193 ops/ms
Iteration   2: 8.192 ops/ms
Iteration   3: 8.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.141 ±(99.9%) 1.628 ops/ms [Average]
  (min, avg, max) = (8.038, 8.141, 8.193), stdev = 0.089
  CI (99.9%): [6.513, 9.769] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.077 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.002 ms/op
Iteration   1: 3.018 ±(99.9%) 0.002 ms/op
Iteration   2: 3.044 ±(99.9%) 0.003 ms/op
Iteration   3: 3.001 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.021 ±(99.9%) 0.396 ms/op [Average]
  (min, avg, max) = (3.001, 3.021, 3.044), stdev = 0.022
  CI (99.9%): [2.625, 3.417] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.007 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.914 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.908 ±(99.9%) 0.004 ms/op
Iteration   1: 2.878 ±(99.9%) 0.005 ms/op
Iteration   2: 2.796 ±(99.9%) 0.004 ms/op
Iteration   3: 2.891 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.855 ±(99.9%) 0.935 ms/op [Average]
  (min, avg, max) = (2.796, 2.855, 2.891), stdev = 0.051
  CI (99.9%): [1.920, 3.790] (assumes normal distribution)


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
# Warmup Iteration   1: 3.781 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.004 ms/op
Iteration   1: 3.002 ±(99.9%) 0.003 ms/op
Iteration   2: 2.985 ±(99.9%) 0.002 ms/op
Iteration   3: 2.998 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.995 ±(99.9%) 0.167 ms/op [Average]
  (min, avg, max) = (2.985, 2.995, 3.002), stdev = 0.009
  CI (99.9%): [2.828, 3.162] (assumes normal distribution)


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
# Warmup Iteration   1: 5.449 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.033 ms/op
Iteration   1: 3.929 ±(99.9%) 0.006 ms/op
Iteration   2: 3.929 ±(99.9%) 0.023 ms/op
Iteration   3: 3.901 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.919 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (3.901, 3.919, 3.929), stdev = 0.016
  CI (99.9%): [3.626, 4.213] (assumes normal distribution)


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
# Warmup Iteration   1: 4.052 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  6.579 ms/op
                 createUser·p0.9999: 19.904 ms/op
                 createUser·p1.00:   20.316 ms/op

Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  9.628 ms/op
                 createUser·p0.9999: 13.378 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   3: 2.993 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.544 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  6.931 ms/op
                 createUser·p0.9999: 22.544 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317402
  mean =      3.023 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25547 
    [ 2.500,  5.000) = 290578 
    [ 5.000,  7.500) = 962 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.465 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     22.801 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.885 ±(99.9%) 0.006 ms/op
Iteration   1: 2.855 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  7.963 ms/op
                 existUser·p0.9999: 12.494 ms/op
                 existUser·p1.00:   12.698 ms/op

Iteration   2: 2.893 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  9.585 ms/op
                 existUser·p0.9999: 13.007 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   3: 2.903 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  10.986 ms/op
                 existUser·p0.9999: 26.378 ms/op
                 existUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332942
  mean =      2.883 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37959 
    [ 2.500,  5.000) = 293593 
    [ 5.000,  7.500) = 916 
    [ 7.500, 10.000) = 215 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.277 ms/op
     p(95.0000) =      3.518 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     15.157 ms/op
     p(99.9990) =     26.696 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.414 ms/op
                 getUser·p0.9999: 17.662 ms/op
                 getUser·p1.00:   18.022 ms/op

Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.601 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.860 ms/op
                 getUser·p0.9999: 20.819 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   3: 3.035 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.049 ms/op
                 getUser·p0.9999: 13.693 ms/op
                 getUser·p1.00:   14.287 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319186
  mean =      3.008 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25023 
    [ 2.500,  5.000) = 292703 
    [ 5.000,  7.500) = 1202 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      6.822 ms/op
     p(99.9900) =     19.991 ms/op
     p(99.9990) =     21.123 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 4.911 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.959 ±(99.9%) 0.012 ms/op
Iteration   1: 3.898 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  12.986 ms/op
                 listUser·p0.9999: 14.791 ms/op
                 listUser·p1.00:   15.041 ms/op

Iteration   2: 4.035 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.986 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  15.713 ms/op
                 listUser·p0.9999: 19.532 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 3.974 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.778 ms/op
                 listUser·p0.999:  15.471 ms/op
                 listUser·p0.9999: 27.984 ms/op
                 listUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242037
  mean =      3.968 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3348 
    [ 2.500,  5.000) = 215670 
    [ 5.000,  7.500) = 21587 
    [ 7.500, 10.000) = 924 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 9 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.870 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     29.712 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.664 ± 1.555  ops/ms
ClientGrpc.existUser                       thrpt       3  11.398 ± 1.827  ops/ms
ClientGrpc.getUser                         thrpt       3  10.798 ± 1.615  ops/ms
ClientGrpc.listUser                        thrpt       3   8.141 ± 1.628  ops/ms
ClientGrpc.createUser                       avgt       3   3.021 ± 0.396   ms/op
ClientGrpc.existUser                        avgt       3   2.855 ± 0.935   ms/op
ClientGrpc.getUser                          avgt       3   2.995 ± 0.167   ms/op
ClientGrpc.listUser                         avgt       3   3.919 ± 0.293   ms/op
ClientGrpc.createUser                     sample  317402   3.023 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.544           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.465           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.660           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.938           ms/op
ClientGrpc.existUser                      sample  332942   2.883 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.715           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.277           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.388           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.157           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.804           ms/op
ClientGrpc.getUser                        sample  319186   3.008 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.601           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.822           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.991           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.234           ms/op
ClientGrpc.listUser                       sample  242037   3.968 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.870           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.565           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.492           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.015           ms/op
