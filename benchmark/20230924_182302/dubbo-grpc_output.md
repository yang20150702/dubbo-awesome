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
# Warmup Iteration   1: 3.387 ops/ms
# Warmup Iteration   2: 7.326 ops/ms
# Warmup Iteration   3: 8.368 ops/ms
Iteration   1: 8.705 ops/ms
Iteration   2: 8.599 ops/ms
Iteration   3: 8.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.706 ±(99.9%) 1.950 ops/ms [Average]
  (min, avg, max) = (8.599, 8.706, 8.813), stdev = 0.107
  CI (99.9%): [6.756, 10.656] (assumes normal distribution)


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
# Warmup Iteration   1: 5.791 ops/ms
# Warmup Iteration   2: 8.449 ops/ms
# Warmup Iteration   3: 8.899 ops/ms
Iteration   1: 9.241 ops/ms
Iteration   2: 9.133 ops/ms
Iteration   3: 8.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.118 ±(99.9%) 2.386 ops/ms [Average]
  (min, avg, max) = (8.981, 9.118, 9.241), stdev = 0.131
  CI (99.9%): [6.732, 11.505] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.795 ops/ms
# Warmup Iteration   2: 8.417 ops/ms
# Warmup Iteration   3: 8.276 ops/ms
Iteration   1: 8.544 ops/ms
Iteration   2: 8.514 ops/ms
Iteration   3: 8.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.555 ±(99.9%) 0.861 ops/ms [Average]
  (min, avg, max) = (8.514, 8.555, 8.607), stdev = 0.047
  CI (99.9%): [7.694, 9.416] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.532 ops/ms
# Warmup Iteration   2: 6.544 ops/ms
# Warmup Iteration   3: 6.771 ops/ms
Iteration   1: 6.943 ops/ms
Iteration   2: 7.034 ops/ms
Iteration   3: 6.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.900 ±(99.9%) 2.911 ops/ms [Average]
  (min, avg, max) = (6.724, 6.900, 7.034), stdev = 0.160
  CI (99.9%): [3.989, 9.812] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.384 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.827 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.008 ms/op
Iteration   1: 3.673 ±(99.9%) 0.003 ms/op
Iteration   2: 3.715 ±(99.9%) 0.003 ms/op
Iteration   3: 3.725 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.704 ±(99.9%) 0.498 ms/op [Average]
  (min, avg, max) = (3.673, 3.704, 3.725), stdev = 0.027
  CI (99.9%): [3.206, 4.202] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.949 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.688 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.486 ±(99.9%) 0.003 ms/op
Iteration   1: 3.446 ±(99.9%) 0.003 ms/op
Iteration   2: 3.538 ±(99.9%) 0.002 ms/op
Iteration   3: 3.453 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.479 ±(99.9%) 0.931 ms/op [Average]
  (min, avg, max) = (3.446, 3.479, 3.538), stdev = 0.051
  CI (99.9%): [2.548, 4.410] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.350 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.004 ms/op
Iteration   1: 3.673 ±(99.9%) 0.003 ms/op
Iteration   2: 3.637 ±(99.9%) 0.003 ms/op
Iteration   3: 3.690 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.667 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (3.637, 3.667, 3.690), stdev = 0.027
  CI (99.9%): [3.170, 4.164] (assumes normal distribution)


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
# Warmup Iteration   1: 6.052 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.011 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.727 ±(99.9%) 0.025 ms/op
Iteration   1: 4.628 ±(99.9%) 0.012 ms/op
Iteration   2: 4.559 ±(99.9%) 0.016 ms/op
Iteration   3: 4.591 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.592 ±(99.9%) 0.624 ms/op [Average]
  (min, avg, max) = (4.559, 4.592, 4.628), stdev = 0.034
  CI (99.9%): [3.968, 5.217] (assumes normal distribution)


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
# Warmup Iteration   1: 5.189 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.692 ±(99.9%) 0.009 ms/op
Iteration   1: 3.681 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.719 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  9.388 ms/op
                 createUser·p0.9999: 19.530 ms/op
                 createUser·p1.00:   19.759 ms/op

Iteration   2: 3.677 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.809 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  9.109 ms/op
                 createUser·p0.9999: 22.386 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   3: 3.660 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.628 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  12.554 ms/op
                 createUser·p0.9999: 23.471 ms/op
                 createUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261365
  mean =      3.673 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5777 
    [ 2.500,  5.000) = 248115 
    [ 5.000,  7.500) = 6423 
    [ 7.500, 10.000) = 819 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =      9.595 ms/op
     p(99.9900) =     23.195 ms/op
     p(99.9990) =     23.835 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 4.785 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.007 ms/op
Iteration   1: 3.452 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.473 ms/op
                 existUser·p0.50:   3.396 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  12.341 ms/op
                 existUser·p0.9999: 15.654 ms/op
                 existUser·p1.00:   15.794 ms/op

Iteration   2: 3.656 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  11.108 ms/op
                 existUser·p0.9999: 15.225 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   3: 3.505 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.828 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  15.545 ms/op
                 existUser·p0.9999: 20.013 ms/op
                 existUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 271382
  mean =      3.536 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6396 
    [ 2.500,  5.000) = 259510 
    [ 5.000,  7.500) = 4555 
    [ 7.500, 10.000) = 541 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     11.151 ms/op
     p(99.9900) =     18.411 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


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
# Warmup Iteration   1: 5.041 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.010 ms/op
Iteration   1: 3.750 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.711 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.060 ms/op
                 getUser·p0.999:  12.485 ms/op
                 getUser·p0.9999: 25.360 ms/op
                 getUser·p1.00:   26.444 ms/op

Iteration   2: 3.701 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  10.273 ms/op
                 getUser·p0.9999: 27.471 ms/op
                 getUser·p1.00:   28.049 ms/op

Iteration   3: 3.701 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   6.185 ms/op
                 getUser·p0.999:  10.353 ms/op
                 getUser·p0.9999: 30.092 ms/op
                 getUser·p1.00:   30.278 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 258305
  mean =      3.717 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7421 
    [ 2.500,  5.000) = 242621 
    [ 5.000,  7.500) = 7137 
    [ 7.500, 10.000) = 827 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     10.469 ms/op
     p(99.9900) =     29.005 ms/op
     p(99.9990) =     30.245 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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
# Warmup Iteration   1: 5.957 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.042 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.695 ±(99.9%) 0.014 ms/op
Iteration   1: 4.641 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.365 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  15.551 ms/op
                 listUser·p0.9999: 18.807 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   2: 4.543 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.152 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 27.983 ms/op
                 listUser·p1.00:   29.164 ms/op

Iteration   3: 4.659 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.004 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.218 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  18.611 ms/op
                 listUser·p0.9999: 21.893 ms/op
                 listUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208017
  mean =      4.614 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 270 
    [ 2.500,  5.000) = 173205 
    [ 5.000,  7.500) = 30828 
    [ 7.500, 10.000) = 3118 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      4.481 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      6.242 ms/op
     p(99.0000) =      7.979 ms/op
     p(99.9000) =     17.137 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     28.913 ms/op
     p(99.9999) =     29.164 ms/op
    p(100.0000) =     29.164 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.706 ± 1.950  ops/ms
ClientGrpc.existUser                       thrpt       3   9.118 ± 2.386  ops/ms
ClientGrpc.getUser                         thrpt       3   8.555 ± 0.861  ops/ms
ClientGrpc.listUser                        thrpt       3   6.900 ± 2.911  ops/ms
ClientGrpc.createUser                       avgt       3   3.704 ± 0.498   ms/op
ClientGrpc.existUser                        avgt       3   3.479 ± 0.931   ms/op
ClientGrpc.getUser                          avgt       3   3.667 ± 0.497   ms/op
ClientGrpc.listUser                         avgt       3   4.592 ± 0.624   ms/op
ClientGrpc.createUser                     sample  261365   3.673 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.851           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.013           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.595           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.195           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.888           ms/op
ClientGrpc.existUser                      sample  271382   3.536 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.473           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.461           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.710           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.151           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.411           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.316           ms/op
ClientGrpc.getUser                        sample  258305   3.717 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.711           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.136           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.469           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.005           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.278           ms/op
ClientGrpc.listUser                       sample  208017   4.614 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.004           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.481           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.242           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.979           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.137           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.345           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.164           ms/op
