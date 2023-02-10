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
# Warmup Iteration   1: 5.074 ops/ms
# Warmup Iteration   2: 8.933 ops/ms
# Warmup Iteration   3: 10.085 ops/ms
Iteration   1: 10.269 ops/ms
Iteration   2: 10.300 ops/ms
Iteration   3: 10.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.355 ±(99.9%) 2.257 ops/ms [Average]
  (min, avg, max) = (10.269, 10.355, 10.497), stdev = 0.124
  CI (99.9%): [8.098, 12.612] (assumes normal distribution)


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
# Warmup Iteration   1: 8.014 ops/ms
# Warmup Iteration   2: 10.316 ops/ms
# Warmup Iteration   3: 10.798 ops/ms
Iteration   1: 11.110 ops/ms
Iteration   2: 10.781 ops/ms
Iteration   3: 10.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.857 ±(99.9%) 4.095 ops/ms [Average]
  (min, avg, max) = (10.681, 10.857, 11.110), stdev = 0.224
  CI (99.9%): [6.762, 14.952] (assumes normal distribution)


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
# Warmup Iteration   1: 7.827 ops/ms
# Warmup Iteration   2: 10.308 ops/ms
# Warmup Iteration   3: 10.380 ops/ms
Iteration   1: 10.194 ops/ms
Iteration   2: 10.545 ops/ms
Iteration   3: 10.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.418 ±(99.9%) 3.550 ops/ms [Average]
  (min, avg, max) = (10.194, 10.418, 10.545), stdev = 0.195
  CI (99.9%): [6.868, 13.968] (assumes normal distribution)


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
# Warmup Iteration   1: 6.843 ops/ms
# Warmup Iteration   2: 7.833 ops/ms
# Warmup Iteration   3: 7.929 ops/ms
Iteration   1: 8.059 ops/ms
Iteration   2: 8.344 ops/ms
Iteration   3: 8.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.205 ±(99.9%) 2.604 ops/ms [Average]
  (min, avg, max) = (8.059, 8.205, 8.344), stdev = 0.143
  CI (99.9%): [5.601, 10.809] (assumes normal distribution)


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
# Warmup Iteration   1: 4.115 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.002 ms/op
Iteration   1: 3.181 ±(99.9%) 0.002 ms/op
Iteration   2: 3.078 ±(99.9%) 0.001 ms/op
Iteration   3: 3.116 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.125 ±(99.9%) 0.943 ms/op [Average]
  (min, avg, max) = (3.078, 3.125, 3.181), stdev = 0.052
  CI (99.9%): [2.182, 4.068] (assumes normal distribution)


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
# Warmup Iteration   1: 3.626 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.003 ms/op
Iteration   1: 2.845 ±(99.9%) 0.003 ms/op
Iteration   2: 2.912 ±(99.9%) 0.004 ms/op
Iteration   3: 2.957 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.905 ±(99.9%) 1.030 ms/op [Average]
  (min, avg, max) = (2.845, 2.905, 2.957), stdev = 0.056
  CI (99.9%): [1.875, 3.935] (assumes normal distribution)


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.003 ms/op
Iteration   1: 3.057 ±(99.9%) 0.002 ms/op
Iteration   2: 3.063 ±(99.9%) 0.004 ms/op
Iteration   3: 3.015 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.045 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (3.015, 3.045, 3.063), stdev = 0.026
  CI (99.9%): [2.572, 3.518] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.101 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.018 ms/op
Iteration   1: 3.910 ±(99.9%) 0.007 ms/op
Iteration   2: 3.874 ±(99.9%) 0.008 ms/op
Iteration   3: 4.076 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.953 ±(99.9%) 1.966 ms/op [Average]
  (min, avg, max) = (3.874, 3.953, 4.076), stdev = 0.108
  CI (99.9%): [1.987, 5.919] (assumes normal distribution)


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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
Iteration   1: 3.104 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.663 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.948 ms/op
                 createUser·p0.999:  9.011 ms/op
                 createUser·p0.9999: 14.206 ms/op
                 createUser·p1.00:   15.434 ms/op

Iteration   2: 3.037 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.697 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  10.048 ms/op
                 createUser·p0.9999: 16.596 ms/op
                 createUser·p1.00:   16.941 ms/op

Iteration   3: 3.149 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.716 ms/op
                 createUser·p0.999:  7.979 ms/op
                 createUser·p0.9999: 20.015 ms/op
                 createUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310318
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28158 
    [ 2.500,  5.000) = 279676 
    [ 5.000,  7.500) = 1869 
    [ 7.500, 10.000) = 316 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      9.820 ms/op
     p(99.9900) =     18.218 ms/op
     p(99.9990) =     20.280 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 3.722 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.007 ms/op
Iteration   1: 2.940 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.616 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 21.504 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   2: 2.964 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.825 ms/op
                 existUser·p0.9999: 17.421 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   3: 2.992 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  12.386 ms/op
                 existUser·p0.9999: 32.525 ms/op
                 existUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323666
  mean =      2.966 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50775 
    [ 2.500,  5.000) = 271341 
    [ 5.000,  7.500) = 1049 
    [ 7.500, 10.000) = 212 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.634 ms/op
     p(99.9900) =     28.280 ms/op
     p(99.9990) =     33.547 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.007 ms/op
Iteration   1: 3.006 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.437 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.904 ms/op
                 getUser·p0.9999: 18.886 ms/op
                 getUser·p1.00:   19.923 ms/op

Iteration   2: 2.953 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.263 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.394 ms/op
                 getUser·p0.999:  7.297 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   3: 3.074 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.618 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.109 ms/op
                 getUser·p0.9999: 37.984 ms/op
                 getUser·p1.00:   38.142 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318792
  mean =      3.011 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36237 
    [ 2.500,  5.000) = 281232 
    [ 5.000,  7.500) = 1050 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.263 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.102 ms/op
     p(99.9900) =     36.658 ms/op
     p(99.9990) =     38.142 ms/op
     p(99.9999) =     38.142 ms/op
    p(100.0000) =     38.142 ms/op


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
# Warmup Iteration   1: 4.366 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.012 ms/op
Iteration   1: 4.001 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.521 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  13.645 ms/op
                 listUser·p0.9999: 19.660 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   2: 4.022 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  18.863 ms/op
                 listUser·p0.9999: 27.068 ms/op
                 listUser·p1.00:   28.934 ms/op

Iteration   3: 3.956 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  14.243 ms/op
                 listUser·p0.9999: 24.901 ms/op
                 listUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240412
  mean =      3.993 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4800 
    [ 2.500,  5.000) = 204876 
    [ 5.000,  7.500) = 29284 
    [ 7.500, 10.000) = 823 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 72 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     14.919 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     28.749 ms/op
     p(99.9999) =     28.934 ms/op
    p(100.0000) =     28.934 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.355 ± 2.257  ops/ms
ClientGrpc.existUser                       thrpt       3  10.857 ± 4.095  ops/ms
ClientGrpc.getUser                         thrpt       3  10.418 ± 3.550  ops/ms
ClientGrpc.listUser                        thrpt       3   8.205 ± 2.604  ops/ms
ClientGrpc.createUser                       avgt       3   3.125 ± 0.943   ms/op
ClientGrpc.existUser                        avgt       3   2.905 ± 1.030   ms/op
ClientGrpc.getUser                          avgt       3   3.045 ± 0.473   ms/op
ClientGrpc.listUser                         avgt       3   3.953 ± 1.966   ms/op
ClientGrpc.createUser                     sample  310318   3.096 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.663           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.760           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.820           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.218           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.447           ms/op
ClientGrpc.existUser                      sample  323666   2.966 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.616           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.846           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.634           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.280           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.620           ms/op
ClientGrpc.getUser                        sample  318792   3.011 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.263           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.102           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          36.658           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          38.142           ms/op
ClientGrpc.listUser                       sample  240412   3.993 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.521           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.919           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.936           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.934           ms/op
