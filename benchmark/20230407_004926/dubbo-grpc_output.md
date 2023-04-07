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
# Warmup Iteration   1: 2.957 ops/ms
# Warmup Iteration   2: 6.567 ops/ms
# Warmup Iteration   3: 7.949 ops/ms
Iteration   1: 8.121 ops/ms
Iteration   2: 8.499 ops/ms
Iteration   3: 8.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.397 ±(99.9%) 4.405 ops/ms [Average]
  (min, avg, max) = (8.121, 8.397, 8.571), stdev = 0.241
  CI (99.9%): [3.992, 12.802] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.445 ops/ms
# Warmup Iteration   2: 8.661 ops/ms
# Warmup Iteration   3: 9.108 ops/ms
Iteration   1: 9.036 ops/ms
Iteration   2: 9.219 ops/ms
Iteration   3: 9.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.099 ±(99.9%) 1.886 ops/ms [Average]
  (min, avg, max) = (9.036, 9.099, 9.219), stdev = 0.103
  CI (99.9%): [7.213, 10.986] (assumes normal distribution)


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
# Warmup Iteration   1: 5.098 ops/ms
# Warmup Iteration   2: 7.989 ops/ms
# Warmup Iteration   3: 8.375 ops/ms
Iteration   1: 8.655 ops/ms
Iteration   2: 8.705 ops/ms
Iteration   3: 8.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.655 ±(99.9%) 0.922 ops/ms [Average]
  (min, avg, max) = (8.604, 8.655, 8.705), stdev = 0.051
  CI (99.9%): [7.733, 9.578] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.345 ops/ms
# Warmup Iteration   2: 6.121 ops/ms
# Warmup Iteration   3: 6.811 ops/ms
Iteration   1: 6.687 ops/ms
Iteration   2: 6.888 ops/ms
Iteration   3: 6.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.764 ±(99.9%) 1.977 ops/ms [Average]
  (min, avg, max) = (6.687, 6.764, 6.888), stdev = 0.108
  CI (99.9%): [4.787, 8.741] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.191 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.880 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.008 ms/op
Iteration   1: 3.675 ±(99.9%) 0.006 ms/op
Iteration   2: 3.594 ±(99.9%) 0.005 ms/op
Iteration   3: 3.569 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.613 ±(99.9%) 1.003 ms/op [Average]
  (min, avg, max) = (3.569, 3.613, 3.675), stdev = 0.055
  CI (99.9%): [2.609, 4.616] (assumes normal distribution)


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
# Warmup Iteration   1: 5.194 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.004 ms/op
Iteration   1: 3.502 ±(99.9%) 0.005 ms/op
Iteration   2: 3.432 ±(99.9%) 0.004 ms/op
Iteration   3: 3.497 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.477 ±(99.9%) 0.716 ms/op [Average]
  (min, avg, max) = (3.432, 3.477, 3.502), stdev = 0.039
  CI (99.9%): [2.761, 4.193] (assumes normal distribution)


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
# Warmup Iteration   1: 5.469 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.692 ±(99.9%) 0.007 ms/op
Iteration   1: 3.666 ±(99.9%) 0.004 ms/op
Iteration   2: 3.635 ±(99.9%) 0.005 ms/op
Iteration   3: 3.761 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.687 ±(99.9%) 1.206 ms/op [Average]
  (min, avg, max) = (3.635, 3.687, 3.761), stdev = 0.066
  CI (99.9%): [2.481, 4.894] (assumes normal distribution)


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
# Warmup Iteration   1: 6.817 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.925 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.837 ±(99.9%) 0.021 ms/op
Iteration   1: 4.766 ±(99.9%) 0.023 ms/op
Iteration   2: 4.659 ±(99.9%) 0.012 ms/op
Iteration   3: 4.746 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.723 ±(99.9%) 1.036 ms/op [Average]
  (min, avg, max) = (4.659, 4.723, 4.766), stdev = 0.057
  CI (99.9%): [3.688, 5.759] (assumes normal distribution)


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
# Warmup Iteration   1: 5.086 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.791 ±(99.9%) 0.009 ms/op
Iteration   1: 3.707 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.358 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   5.581 ms/op
                 createUser·p0.999:  11.549 ms/op
                 createUser·p0.9999: 15.751 ms/op
                 createUser·p1.00:   16.122 ms/op

Iteration   2: 3.687 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.001 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.593 ms/op
                 createUser·p0.999:  13.110 ms/op
                 createUser·p0.9999: 18.252 ms/op
                 createUser·p1.00:   18.612 ms/op

Iteration   3: 3.726 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.465 ms/op
                 createUser·p0.99:   5.120 ms/op
                 createUser·p0.999:  16.984 ms/op
                 createUser·p0.9999: 18.882 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259052
  mean =      3.707 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 6180 
    [ 2.500,  3.750) = 140219 
    [ 3.750,  5.000) = 107806 
    [ 5.000,  6.250) = 3383 
    [ 6.250,  7.500) = 440 
    [ 7.500,  8.750) = 248 
    [ 8.750, 10.000) = 178 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 104 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 62 
    [16.250, 17.500) = 64 
    [17.500, 18.750) = 48 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.439 ms/op
     p(99.9000) =     12.844 ms/op
     p(99.9900) =     18.222 ms/op
     p(99.9990) =     19.688 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 4.869 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.016 ms/op
Iteration   1: 3.416 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  7.186 ms/op
                 existUser·p0.9999: 26.014 ms/op
                 existUser·p1.00:   26.313 ms/op

Iteration   2: 3.545 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   4.059 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.585 ms/op
                 existUser·p0.999:  11.671 ms/op
                 existUser·p0.9999: 16.152 ms/op
                 existUser·p1.00:   17.433 ms/op

Iteration   3: 3.539 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  11.387 ms/op
                 existUser·p0.9999: 21.100 ms/op
                 existUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274872
  mean =      3.499 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11955 
    [ 2.500,  5.000) = 257978 
    [ 5.000,  7.500) = 4319 
    [ 7.500, 10.000) = 277 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.681 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     11.026 ms/op
     p(99.9900) =     25.445 ms/op
     p(99.9990) =     26.190 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 5.539 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.679 ±(99.9%) 0.008 ms/op
Iteration   1: 3.720 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.018 ms/op
                 getUser·p0.50:   3.682 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  11.485 ms/op
                 getUser·p0.9999: 15.480 ms/op
                 getUser·p1.00:   15.827 ms/op

Iteration   2: 3.662 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   3.637 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.415 ms/op
                 getUser·p0.999:  11.431 ms/op
                 getUser·p0.9999: 15.422 ms/op
                 getUser·p1.00:   16.531 ms/op

Iteration   3: 3.612 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  8.219 ms/op
                 getUser·p0.9999: 19.960 ms/op
                 getUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261919
  mean =      3.665 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9728 
    [ 2.500,  5.000) = 246316 
    [ 5.000,  7.500) = 5290 
    [ 7.500, 10.000) = 306 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     10.931 ms/op
     p(99.9900) =     19.121 ms/op
     p(99.9990) =     20.276 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 5.768 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.205 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.814 ±(99.9%) 0.013 ms/op
Iteration   1: 4.791 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.627 ms/op
                 listUser·p0.99:   8.004 ms/op
                 listUser·p0.999:  16.404 ms/op
                 listUser·p0.9999: 19.059 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   2: 4.713 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.577 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.906 ms/op
                 listUser·p0.95:   6.603 ms/op
                 listUser·p0.99:   8.171 ms/op
                 listUser·p0.999:  17.532 ms/op
                 listUser·p0.9999: 19.517 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 4.738 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.784 ms/op
                 listUser·p0.95:   6.545 ms/op
                 listUser·p0.99:   8.119 ms/op
                 listUser·p0.999:  17.479 ms/op
                 listUser·p0.9999: 18.784 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202336
  mean =      4.747 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 264 
    [ 2.500,  5.000) = 156183 
    [ 5.000,  7.500) = 41601 
    [ 7.500, 10.000) = 3856 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 159 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.833 ms/op
     p(95.0000) =      6.595 ms/op
     p(99.0000) =      8.102 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     19.194 ms/op
     p(99.9990) =     20.473 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.397 ± 4.405  ops/ms
ClientGrpc.existUser                       thrpt       3   9.099 ± 1.886  ops/ms
ClientGrpc.getUser                         thrpt       3   8.655 ± 0.922  ops/ms
ClientGrpc.listUser                        thrpt       3   6.764 ± 1.977  ops/ms
ClientGrpc.createUser                       avgt       3   3.613 ± 1.003   ms/op
ClientGrpc.existUser                        avgt       3   3.477 ± 0.716   ms/op
ClientGrpc.getUser                          avgt       3   3.687 ± 1.206   ms/op
ClientGrpc.listUser                         avgt       3   4.723 ± 1.036   ms/op
ClientGrpc.createUser                     sample  259052   3.707 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.823           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.439           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.844           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.222           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.792           ms/op
ClientGrpc.existUser                      sample  274872   3.499 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.681           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.055           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.587           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.026           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.445           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.313           ms/op
ClientGrpc.getUser                        sample  261919   3.665 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.931           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.931           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.121           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.414           ms/op
ClientGrpc.listUser                       sample  202336   4.747 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.307           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.102           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.072           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.194           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.972           ms/op
