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
# Warmup Iteration   1: 3.527 ops/ms
# Warmup Iteration   2: 7.920 ops/ms
# Warmup Iteration   3: 8.823 ops/ms
Iteration   1: 9.634 ops/ms
Iteration   2: 9.456 ops/ms
Iteration   3: 9.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.508 ±(99.9%) 2.011 ops/ms [Average]
  (min, avg, max) = (9.433, 9.508, 9.634), stdev = 0.110
  CI (99.9%): [7.497, 11.519] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.456 ops/ms
# Warmup Iteration   2: 9.582 ops/ms
# Warmup Iteration   3: 9.812 ops/ms
Iteration   1: 9.971 ops/ms
Iteration   2: 9.798 ops/ms
Iteration   3: 9.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.898 ±(99.9%) 1.631 ops/ms [Average]
  (min, avg, max) = (9.798, 9.898, 9.971), stdev = 0.089
  CI (99.9%): [8.267, 11.528] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.836 ops/ms
# Warmup Iteration   2: 8.921 ops/ms
# Warmup Iteration   3: 9.300 ops/ms
Iteration   1: 9.393 ops/ms
Iteration   2: 9.139 ops/ms
Iteration   3: 9.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.328 ±(99.9%) 3.042 ops/ms [Average]
  (min, avg, max) = (9.139, 9.328, 9.453), stdev = 0.167
  CI (99.9%): [6.286, 12.370] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.755 ops/ms
# Warmup Iteration   2: 7.026 ops/ms
# Warmup Iteration   3: 7.207 ops/ms
Iteration   1: 7.262 ops/ms
Iteration   2: 7.140 ops/ms
Iteration   3: 7.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.176 ±(99.9%) 1.376 ops/ms [Average]
  (min, avg, max) = (7.124, 7.176, 7.262), stdev = 0.075
  CI (99.9%): [5.799, 8.552] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.899 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.003 ms/op
Iteration   1: 3.520 ±(99.9%) 0.002 ms/op
Iteration   2: 3.547 ±(99.9%) 0.003 ms/op
Iteration   3: 3.393 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.487 ±(99.9%) 1.499 ms/op [Average]
  (min, avg, max) = (3.393, 3.487, 3.547), stdev = 0.082
  CI (99.9%): [1.988, 4.985] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.413 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.317 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.233 ±(99.9%) 0.003 ms/op
Iteration   1: 3.238 ±(99.9%) 0.002 ms/op
Iteration   2: 3.275 ±(99.9%) 0.001 ms/op
Iteration   3: 3.175 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.229 ±(99.9%) 0.919 ms/op [Average]
  (min, avg, max) = (3.175, 3.229, 3.275), stdev = 0.050
  CI (99.9%): [2.311, 4.148] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.904 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.004 ms/op
Iteration   1: 3.372 ±(99.9%) 0.004 ms/op
Iteration   2: 3.416 ±(99.9%) 0.003 ms/op
Iteration   3: 3.352 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.380 ±(99.9%) 0.595 ms/op [Average]
  (min, avg, max) = (3.352, 3.380, 3.416), stdev = 0.033
  CI (99.9%): [2.785, 3.975] (assumes normal distribution)


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
# Warmup Iteration   1: 6.475 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.625 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.494 ±(99.9%) 0.014 ms/op
Iteration   1: 4.414 ±(99.9%) 0.021 ms/op
Iteration   2: 4.415 ±(99.9%) 0.028 ms/op
Iteration   3: 4.463 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.431 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (4.414, 4.431, 4.463), stdev = 0.028
  CI (99.9%): [3.918, 4.944] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.994 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.577 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.431 ±(99.9%) 0.009 ms/op
Iteration   1: 3.364 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.845 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  10.008 ms/op
                 createUser·p0.9999: 23.035 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 3.421 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  12.880 ms/op
                 createUser·p0.9999: 20.391 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   3: 3.418 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.902 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  11.197 ms/op
                 createUser·p0.9999: 37.856 ms/op
                 createUser·p1.00:   38.535 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 282280
  mean =      3.401 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13129 
    [ 2.500,  5.000) = 264687 
    [ 5.000,  7.500) = 3616 
    [ 7.500, 10.000) = 543 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     10.224 ms/op
     p(99.9900) =     36.801 ms/op
     p(99.9990) =     38.057 ms/op
     p(99.9999) =     38.535 ms/op
    p(100.0000) =     38.535 ms/op


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
# Warmup Iteration   1: 4.675 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.007 ms/op
Iteration   1: 3.237 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   4.973 ms/op
                 existUser·p0.999:  7.737 ms/op
                 existUser·p0.9999: 14.485 ms/op
                 existUser·p1.00:   14.664 ms/op

Iteration   2: 3.199 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  8.061 ms/op
                 existUser·p0.9999: 17.793 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   3: 3.263 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.071 ms/op
                 existUser·p0.999:  7.731 ms/op
                 existUser·p0.9999: 20.126 ms/op
                 existUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 296949
  mean =      3.233 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17086 
    [ 2.500,  5.000) = 277264 
    [ 5.000,  7.500) = 2235 
    [ 7.500, 10.000) = 198 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.026 ms/op
     p(99.0000) =      4.891 ms/op
     p(99.9000) =      7.791 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     20.416 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 4.855 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.516 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.007 ms/op
Iteration   1: 3.440 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  12.158 ms/op
                 getUser·p0.9999: 19.553 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   2: 3.433 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   5.226 ms/op
                 getUser·p0.999:  9.329 ms/op
                 getUser·p0.9999: 14.560 ms/op
                 getUser·p1.00:   14.893 ms/op

Iteration   3: 3.356 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.889 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   5.153 ms/op
                 getUser·p0.999:  8.536 ms/op
                 getUser·p0.9999: 18.119 ms/op
                 getUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 281573
  mean =      3.409 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11533 
    [ 2.500,  5.000) = 265888 
    [ 5.000,  7.500) = 3482 
    [ 7.500, 10.000) = 353 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     10.732 ms/op
     p(99.9900) =     19.056 ms/op
     p(99.9990) =     20.083 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 5.924 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.558 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.512 ±(99.9%) 0.015 ms/op
Iteration   1: 4.476 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.749 ms/op
                 listUser·p0.50:   4.252 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   6.636 ms/op
                 listUser·p0.99:   8.266 ms/op
                 listUser·p0.999:  15.139 ms/op
                 listUser·p0.9999: 16.728 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   2: 4.334 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.716 ms/op
                 listUser·p0.50:   4.170 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   6.259 ms/op
                 listUser·p0.99:   7.995 ms/op
                 listUser·p0.999:  17.635 ms/op
                 listUser·p0.9999: 21.266 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   3: 4.464 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.034 ms/op
                 listUser·p0.50:   4.276 ms/op
                 listUser·p0.90:   5.595 ms/op
                 listUser·p0.95:   6.373 ms/op
                 listUser·p0.99:   8.176 ms/op
                 listUser·p0.999:  18.481 ms/op
                 listUser·p0.9999: 25.744 ms/op
                 listUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 217157
  mean =      4.424 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1118 
    [ 2.500,  5.000) = 178792 
    [ 5.000,  7.500) = 33351 
    [ 7.500, 10.000) = 3141 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.628 ms/op
     p(95.0000) =      6.439 ms/op
     p(99.0000) =      8.151 ms/op
     p(99.9000) =     15.991 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     26.078 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.508 ± 2.011  ops/ms
ClientGrpc.existUser                       thrpt       3   9.898 ± 1.631  ops/ms
ClientGrpc.getUser                         thrpt       3   9.328 ± 3.042  ops/ms
ClientGrpc.listUser                        thrpt       3   7.176 ± 1.376  ops/ms
ClientGrpc.createUser                       avgt       3   3.487 ± 1.499   ms/op
ClientGrpc.existUser                        avgt       3   3.229 ± 0.919   ms/op
ClientGrpc.getUser                          avgt       3   3.380 ± 0.595   ms/op
ClientGrpc.listUser                         avgt       3   4.431 ± 0.513   ms/op
ClientGrpc.createUser                     sample  282280   3.401 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.845           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.351           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.035           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.439           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.224           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          36.801           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          38.535           ms/op
ClientGrpc.existUser                      sample  296949   3.233 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.876           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.203           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.026           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.891           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.791           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.088           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.578           ms/op
ClientGrpc.getUser                        sample  281573   3.409 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.658           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.363           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.047           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.732           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.056           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.677           ms/op
ClientGrpc.listUser                       sample  217157   4.424 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.716           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.235           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.439           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.151           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.991           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.510           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.182           ms/op
