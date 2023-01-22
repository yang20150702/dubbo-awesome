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
# Warmup Iteration   1: 4.469 ops/ms
# Warmup Iteration   2: 9.340 ops/ms
# Warmup Iteration   3: 10.197 ops/ms
Iteration   1: 9.963 ops/ms
Iteration   2: 10.386 ops/ms
Iteration   3: 10.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.203 ±(99.9%) 3.962 ops/ms [Average]
  (min, avg, max) = (9.963, 10.203, 10.386), stdev = 0.217
  CI (99.9%): [6.241, 14.165] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.994 ops/ms
# Warmup Iteration   2: 10.301 ops/ms
# Warmup Iteration   3: 10.650 ops/ms
Iteration   1: 10.649 ops/ms
Iteration   2: 10.655 ops/ms
Iteration   3: 10.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.689 ±(99.9%) 1.181 ops/ms [Average]
  (min, avg, max) = (10.649, 10.689, 10.764), stdev = 0.065
  CI (99.9%): [9.508, 11.870] (assumes normal distribution)


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
# Warmup Iteration   1: 7.662 ops/ms
# Warmup Iteration   2: 9.868 ops/ms
# Warmup Iteration   3: 10.174 ops/ms
Iteration   1: 9.978 ops/ms
Iteration   2: 10.020 ops/ms
Iteration   3: 10.198 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.065 ±(99.9%) 2.127 ops/ms [Average]
  (min, avg, max) = (9.978, 10.065, 10.198), stdev = 0.117
  CI (99.9%): [7.938, 12.193] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.708 ops/ms
# Warmup Iteration   2: 7.557 ops/ms
# Warmup Iteration   3: 7.925 ops/ms
Iteration   1: 7.880 ops/ms
Iteration   2: 8.160 ops/ms
Iteration   3: 8.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.032 ±(99.9%) 2.582 ops/ms [Average]
  (min, avg, max) = (7.880, 8.032, 8.160), stdev = 0.142
  CI (99.9%): [5.450, 10.614] (assumes normal distribution)


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
# Warmup Iteration   1: 4.210 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.002 ms/op
Iteration   1: 3.108 ±(99.9%) 0.002 ms/op
Iteration   2: 3.224 ±(99.9%) 0.002 ms/op
Iteration   3: 3.173 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.169 ±(99.9%) 1.057 ms/op [Average]
  (min, avg, max) = (3.108, 3.169, 3.224), stdev = 0.058
  CI (99.9%): [2.112, 4.225] (assumes normal distribution)


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
# Warmup Iteration   1: 3.899 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.002 ms/op
Iteration   1: 2.955 ±(99.9%) 0.003 ms/op
Iteration   2: 3.033 ±(99.9%) 0.002 ms/op
Iteration   3: 3.009 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.999 ±(99.9%) 0.721 ms/op [Average]
  (min, avg, max) = (2.955, 2.999, 3.033), stdev = 0.040
  CI (99.9%): [2.278, 3.720] (assumes normal distribution)


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
# Warmup Iteration   1: 3.859 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.003 ms/op
Iteration   1: 3.159 ±(99.9%) 0.002 ms/op
Iteration   2: 3.092 ±(99.9%) 0.004 ms/op
Iteration   3: 3.088 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.113 ±(99.9%) 0.727 ms/op [Average]
  (min, avg, max) = (3.088, 3.113, 3.159), stdev = 0.040
  CI (99.9%): [2.386, 3.840] (assumes normal distribution)


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
# Warmup Iteration   1: 4.342 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.024 ms/op
Iteration   1: 4.011 ±(99.9%) 0.014 ms/op
Iteration   2: 3.946 ±(99.9%) 0.012 ms/op
Iteration   3: 3.915 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.957 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (3.915, 3.957, 4.011), stdev = 0.049
  CI (99.9%): [3.062, 4.853] (assumes normal distribution)


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
# Warmup Iteration   1: 4.158 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.007 ms/op
Iteration   1: 3.068 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.244 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  10.475 ms/op
                 createUser·p0.9999: 14.912 ms/op
                 createUser·p1.00:   15.368 ms/op

Iteration   2: 3.173 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  9.333 ms/op
                 createUser·p0.9999: 13.631 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   3: 3.149 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.689 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  6.882 ms/op
                 createUser·p0.9999: 16.908 ms/op
                 createUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306595
  mean =      3.130 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1003 
    [ 1.250,  2.500) = 16639 
    [ 2.500,  3.750) = 260146 
    [ 3.750,  5.000) = 27253 
    [ 5.000,  6.250) = 734 
    [ 6.250,  7.500) = 310 
    [ 7.500,  8.750) = 106 
    [ 8.750, 10.000) = 98 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.244 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =     10.001 ms/op
     p(99.9900) =     16.428 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 3.900 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
Iteration   1: 2.965 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.192 ms/op
                 existUser·p0.999:  5.692 ms/op
                 existUser·p0.9999: 11.771 ms/op
                 existUser·p1.00:   12.042 ms/op

Iteration   2: 3.025 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  8.989 ms/op
                 existUser·p0.9999: 21.234 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.795 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.069 ms/op
                 existUser·p0.9999: 13.779 ms/op
                 existUser·p1.00:   14.090 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317117
  mean =      3.024 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38251 
    [ 2.500,  5.000) = 278158 
    [ 5.000,  7.500) = 406 
    [ 7.500, 10.000) = 146 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.365 ms/op
     p(99.9900) =     20.466 ms/op
     p(99.9990) =     21.708 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 3.923 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.006 ms/op
Iteration   1: 3.102 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.668 ms/op
                 getUser·p0.9999: 14.724 ms/op
                 getUser·p1.00:   16.073 ms/op

Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  10.519 ms/op
                 getUser·p0.9999: 16.173 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   3: 3.121 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.521 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.606 ms/op
                 getUser·p0.9999: 17.448 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307438
  mean =      3.122 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1412 
    [ 1.250,  2.500) = 17962 
    [ 2.500,  3.750) = 259646 
    [ 3.750,  5.000) = 27222 
    [ 5.000,  6.250) = 645 
    [ 6.250,  7.500) = 233 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 81 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.521 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.668 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     17.886 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.368 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.100 ±(99.9%) 0.012 ms/op
Iteration   1: 4.000 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.323 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  13.455 ms/op
                 listUser·p0.9999: 19.562 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   2: 4.154 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  16.302 ms/op
                 listUser·p0.9999: 18.350 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   3: 4.116 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.775 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  16.482 ms/op
                 listUser·p0.9999: 21.650 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234643
  mean =      4.089 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2950 
    [ 2.500,  5.000) = 200861 
    [ 5.000,  7.500) = 29274 
    [ 7.500, 10.000) = 1049 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      7.078 ms/op
     p(99.9000) =     16.253 ms/op
     p(99.9900) =     21.072 ms/op
     p(99.9990) =     21.986 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.203 ± 3.962  ops/ms
ClientGrpc.existUser                       thrpt       3  10.689 ± 1.181  ops/ms
ClientGrpc.getUser                         thrpt       3  10.065 ± 2.127  ops/ms
ClientGrpc.listUser                        thrpt       3   8.032 ± 2.582  ops/ms
ClientGrpc.createUser                       avgt       3   3.169 ± 1.057   ms/op
ClientGrpc.existUser                        avgt       3   2.999 ± 0.721   ms/op
ClientGrpc.getUser                          avgt       3   3.113 ± 0.727   ms/op
ClientGrpc.listUser                         avgt       3   3.957 ± 0.896   ms/op
ClientGrpc.createUser                     sample  306595   3.130 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.244           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.940           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.001           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.428           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.974           ms/op
ClientGrpc.existUser                      sample  317117   3.024 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.703           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.006           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.365           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.466           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.889           ms/op
ClientGrpc.getUser                        sample  307438   3.122 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.521           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.668           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.974           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.153           ms/op
ClientGrpc.listUser                       sample  234643   4.089 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.775           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.841           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.078           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.253           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.072           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.020           ms/op
