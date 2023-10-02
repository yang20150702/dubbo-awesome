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
# Warmup Iteration   1: 3.430 ops/ms
# Warmup Iteration   2: 7.198 ops/ms
# Warmup Iteration   3: 8.186 ops/ms
Iteration   1: 8.613 ops/ms
Iteration   2: 8.551 ops/ms
Iteration   3: 8.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.587 ±(99.9%) 0.583 ops/ms [Average]
  (min, avg, max) = (8.551, 8.587, 8.613), stdev = 0.032
  CI (99.9%): [8.004, 9.170] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.759 ops/ms
# Warmup Iteration   2: 8.623 ops/ms
# Warmup Iteration   3: 8.959 ops/ms
Iteration   1: 9.228 ops/ms
Iteration   2: 9.167 ops/ms
Iteration   3: 9.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.164 ±(99.9%) 1.211 ops/ms [Average]
  (min, avg, max) = (9.096, 9.164, 9.228), stdev = 0.066
  CI (99.9%): [7.953, 10.374] (assumes normal distribution)


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
# Warmup Iteration   1: 5.478 ops/ms
# Warmup Iteration   2: 8.364 ops/ms
# Warmup Iteration   3: 8.579 ops/ms
Iteration   1: 8.858 ops/ms
Iteration   2: 8.668 ops/ms
Iteration   3: 8.706 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.744 ±(99.9%) 1.833 ops/ms [Average]
  (min, avg, max) = (8.668, 8.744, 8.858), stdev = 0.100
  CI (99.9%): [6.911, 10.577] (assumes normal distribution)


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
# Warmup Iteration   1: 4.464 ops/ms
# Warmup Iteration   2: 6.813 ops/ms
# Warmup Iteration   3: 6.994 ops/ms
Iteration   1: 6.910 ops/ms
Iteration   2: 6.935 ops/ms
Iteration   3: 6.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.931 ±(99.9%) 0.361 ops/ms [Average]
  (min, avg, max) = (6.910, 6.931, 6.949), stdev = 0.020
  CI (99.9%): [6.570, 7.293] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.233 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.026 ms/op
Iteration   1: 3.677 ±(99.9%) 0.023 ms/op
Iteration   2: 3.658 ±(99.9%) 0.004 ms/op
Iteration   3: 3.653 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.663 ±(99.9%) 0.229 ms/op [Average]
  (min, avg, max) = (3.653, 3.663, 3.677), stdev = 0.013
  CI (99.9%): [3.434, 3.891] (assumes normal distribution)


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
# Warmup Iteration   1: 4.662 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.598 ±(99.9%) 0.001 ms/op
Iteration   1: 3.554 ±(99.9%) 0.003 ms/op
Iteration   2: 3.550 ±(99.9%) 0.004 ms/op
Iteration   3: 3.472 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.525 ±(99.9%) 0.842 ms/op [Average]
  (min, avg, max) = (3.472, 3.525, 3.554), stdev = 0.046
  CI (99.9%): [2.683, 4.367] (assumes normal distribution)


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
# Warmup Iteration   1: 5.211 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.003 ms/op
Iteration   1: 3.700 ±(99.9%) 0.003 ms/op
Iteration   2: 3.661 ±(99.9%) 0.003 ms/op
Iteration   3: 3.732 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.698 ±(99.9%) 0.653 ms/op [Average]
  (min, avg, max) = (3.661, 3.698, 3.732), stdev = 0.036
  CI (99.9%): [3.044, 4.351] (assumes normal distribution)


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
# Warmup Iteration   1: 6.909 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.808 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.690 ±(99.9%) 0.052 ms/op
Iteration   1: 4.570 ±(99.9%) 0.013 ms/op
Iteration   2: 4.422 ±(99.9%) 0.008 ms/op
Iteration   3: 4.552 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.514 ±(99.9%) 1.476 ms/op [Average]
  (min, avg, max) = (4.422, 4.514, 4.570), stdev = 0.081
  CI (99.9%): [3.039, 5.990] (assumes normal distribution)


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
# Warmup Iteration   1: 5.212 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.682 ±(99.9%) 0.008 ms/op
Iteration   1: 3.705 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.391 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.128 ms/op
                 createUser·p0.999:  9.126 ms/op
                 createUser·p0.9999: 15.364 ms/op
                 createUser·p1.00:   15.565 ms/op

Iteration   2: 3.628 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  7.994 ms/op
                 createUser·p0.9999: 14.028 ms/op
                 createUser·p1.00:   16.663 ms/op

Iteration   3: 3.748 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.702 ms/op
                 createUser·p0.99:   5.824 ms/op
                 createUser·p0.999:  16.752 ms/op
                 createUser·p0.9999: 21.085 ms/op
                 createUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260074
  mean =      3.693 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2705 
    [ 2.500,  5.000) = 253194 
    [ 5.000,  7.500) = 3456 
    [ 7.500, 10.000) = 392 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     11.648 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     22.328 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 4.790 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.762 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.007 ms/op
Iteration   1: 3.579 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   3.531 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  12.135 ms/op
                 existUser·p0.9999: 15.749 ms/op
                 existUser·p1.00:   17.891 ms/op

Iteration   2: 3.438 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.339 ms/op
                 existUser·p0.999:  8.765 ms/op
                 existUser·p0.9999: 16.649 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   3: 3.593 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   3.539 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  11.731 ms/op
                 existUser·p0.9999: 17.302 ms/op
                 existUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271397
  mean =      3.535 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 652 
    [ 1.250,  2.500) = 6842 
    [ 2.500,  3.750) = 182980 
    [ 3.750,  5.000) = 77596 
    [ 5.000,  6.250) = 1971 
    [ 6.250,  7.500) = 535 
    [ 7.500,  8.750) = 431 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     11.233 ms/op
     p(99.9900) =     16.709 ms/op
     p(99.9990) =     19.352 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 5.370 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.008 ms/op
Iteration   1: 3.741 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.026 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   5.219 ms/op
                 getUser·p0.999:  9.184 ms/op
                 getUser·p0.9999: 21.314 ms/op
                 getUser·p1.00:   21.987 ms/op

Iteration   2: 3.740 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.678 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.661 ms/op
                 getUser·p0.99:   5.553 ms/op
                 getUser·p0.999:  8.520 ms/op
                 getUser·p0.9999: 20.739 ms/op
                 getUser·p1.00:   21.103 ms/op

Iteration   3: 3.672 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  8.733 ms/op
                 getUser·p0.9999: 22.957 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 258092
  mean =      3.717 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3814 
    [ 2.500,  5.000) = 249804 
    [ 5.000,  7.500) = 3904 
    [ 7.500, 10.000) = 397 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     21.174 ms/op
     p(99.9990) =     23.146 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 6.357 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.755 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.712 ±(99.9%) 0.011 ms/op
Iteration   1: 4.639 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.063 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.946 ms/op
                 listUser·p0.999:  15.270 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 4.604 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  16.096 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   18.711 ms/op

Iteration   3: 4.594 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.217 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   6.185 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 20.353 ms/op
                 listUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208265
  mean =      4.612 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 238 
    [ 2.500,  5.000) = 176160 
    [ 5.000,  7.500) = 28579 
    [ 7.500, 10.000) = 2742 
    [10.000, 12.500) = 168 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      6.005 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     16.207 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     22.307 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.587 ± 0.583  ops/ms
ClientGrpc.existUser                       thrpt       3   9.164 ± 1.211  ops/ms
ClientGrpc.getUser                         thrpt       3   8.744 ± 1.833  ops/ms
ClientGrpc.listUser                        thrpt       3   6.931 ± 0.361  ops/ms
ClientGrpc.createUser                       avgt       3   3.663 ± 0.229   ms/op
ClientGrpc.existUser                        avgt       3   3.525 ± 0.842   ms/op
ClientGrpc.getUser                          avgt       3   3.698 ± 0.653   ms/op
ClientGrpc.listUser                         avgt       3   4.514 ± 1.476   ms/op
ClientGrpc.createUser                     sample  260074   3.693 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.824           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.648           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.414           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.413           ms/op
ClientGrpc.existUser                      sample  271397   3.535 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.663           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.292           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.233           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.709           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.464           ms/op
ClientGrpc.getUser                        sample  258092   3.717 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.723           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.733           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.174           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.429           ms/op
ClientGrpc.listUser                       sample  208265   4.612 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.063           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.005           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.807           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.207           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.087           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.610           ms/op
