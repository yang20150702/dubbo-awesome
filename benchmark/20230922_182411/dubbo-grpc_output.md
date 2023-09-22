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
# Warmup Iteration   1: 3.179 ops/ms
# Warmup Iteration   2: 7.120 ops/ms
# Warmup Iteration   3: 8.111 ops/ms
Iteration   1: 8.540 ops/ms
Iteration   2: 8.861 ops/ms
Iteration   3: 8.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.704 ±(99.9%) 2.931 ops/ms [Average]
  (min, avg, max) = (8.540, 8.704, 8.861), stdev = 0.161
  CI (99.9%): [5.773, 11.635] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.662 ops/ms
# Warmup Iteration   2: 8.937 ops/ms
# Warmup Iteration   3: 8.995 ops/ms
Iteration   1: 9.148 ops/ms
Iteration   2: 9.174 ops/ms
Iteration   3: 9.057 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.126 ±(99.9%) 1.117 ops/ms [Average]
  (min, avg, max) = (9.057, 9.126, 9.174), stdev = 0.061
  CI (99.9%): [8.009, 10.244] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.567 ops/ms
# Warmup Iteration   2: 8.150 ops/ms
# Warmup Iteration   3: 8.671 ops/ms
Iteration   1: 8.781 ops/ms
Iteration   2: 8.629 ops/ms
Iteration   3: 8.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.583 ±(99.9%) 4.099 ops/ms [Average]
  (min, avg, max) = (8.338, 8.583, 8.781), stdev = 0.225
  CI (99.9%): [4.483, 12.682] (assumes normal distribution)


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
# Warmup Iteration   1: 4.387 ops/ms
# Warmup Iteration   2: 6.343 ops/ms
# Warmup Iteration   3: 6.760 ops/ms
Iteration   1: 6.740 ops/ms
Iteration   2: 6.811 ops/ms
Iteration   3: 6.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.787 ±(99.9%) 0.733 ops/ms [Average]
  (min, avg, max) = (6.740, 6.787, 6.811), stdev = 0.040
  CI (99.9%): [6.054, 7.520] (assumes normal distribution)


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
# Warmup Iteration   1: 5.429 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.868 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.764 ±(99.9%) 0.017 ms/op
Iteration   1: 3.728 ±(99.9%) 0.008 ms/op
Iteration   2: 3.674 ±(99.9%) 0.002 ms/op
Iteration   3: 3.674 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.692 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (3.674, 3.692, 3.728), stdev = 0.031
  CI (99.9%): [3.123, 4.262] (assumes normal distribution)


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
# Warmup Iteration   1: 4.937 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.002 ms/op
Iteration   1: 3.547 ±(99.9%) 0.003 ms/op
Iteration   2: 3.534 ±(99.9%) 0.002 ms/op
Iteration   3: 3.469 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.517 ±(99.9%) 0.756 ms/op [Average]
  (min, avg, max) = (3.469, 3.517, 3.547), stdev = 0.041
  CI (99.9%): [2.761, 4.272] (assumes normal distribution)


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
# Warmup Iteration   1: 5.256 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.929 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.749 ±(99.9%) 0.003 ms/op
Iteration   1: 3.872 ±(99.9%) 0.002 ms/op
Iteration   2: 3.791 ±(99.9%) 0.004 ms/op
Iteration   3: 3.716 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.793 ±(99.9%) 1.425 ms/op [Average]
  (min, avg, max) = (3.716, 3.793, 3.872), stdev = 0.078
  CI (99.9%): [2.368, 5.218] (assumes normal distribution)


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
# Warmup Iteration   1: 7.247 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.702 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.589 ±(99.9%) 0.010 ms/op
Iteration   1: 4.612 ±(99.9%) 0.022 ms/op
Iteration   2: 4.626 ±(99.9%) 0.009 ms/op
Iteration   3: 4.632 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.623 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (4.612, 4.623, 4.632), stdev = 0.010
  CI (99.9%): [4.442, 4.805] (assumes normal distribution)


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
# Warmup Iteration   1: 5.165 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.008 ms/op
Iteration   1: 3.668 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   3.629 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  11.386 ms/op
                 createUser·p0.9999: 14.292 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 3.628 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.251 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  10.551 ms/op
                 createUser·p0.9999: 14.860 ms/op
                 createUser·p1.00:   15.221 ms/op

Iteration   3: 3.640 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.941 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  14.509 ms/op
                 createUser·p0.9999: 21.000 ms/op
                 createUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263144
  mean =      3.645 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5929 
    [ 2.500,  5.000) = 251769 
    [ 5.000,  7.500) = 4391 
    [ 7.500, 10.000) = 653 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     11.548 ms/op
     p(99.9900) =     19.988 ms/op
     p(99.9990) =     21.332 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 4.696 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.452 ±(99.9%) 0.008 ms/op
Iteration   1: 3.502 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.177 ms/op
                 existUser·p0.999:  7.615 ms/op
                 existUser·p0.9999: 16.276 ms/op
                 existUser·p1.00:   16.777 ms/op

Iteration   2: 3.397 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.267 ms/op
                 existUser·p0.999:  7.821 ms/op
                 existUser·p0.9999: 17.170 ms/op
                 existUser·p1.00:   17.924 ms/op

Iteration   3: 3.473 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.104 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  10.862 ms/op
                 existUser·p0.9999: 21.056 ms/op
                 existUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 277672
  mean =      3.457 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10166 
    [ 2.500,  5.000) = 263750 
    [ 5.000,  7.500) = 3269 
    [ 7.500, 10.000) = 276 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.428 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =      8.367 ms/op
     p(99.9900) =     19.366 ms/op
     p(99.9990) =     21.299 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 5.362 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.744 ±(99.9%) 0.009 ms/op
Iteration   1: 3.781 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   3.703 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  12.243 ms/op
                 getUser·p0.9999: 19.580 ms/op
                 getUser·p1.00:   19.988 ms/op

Iteration   2: 3.761 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  8.454 ms/op
                 getUser·p0.9999: 20.758 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   3: 3.815 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.007 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.727 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  10.708 ms/op
                 getUser·p0.9999: 23.396 ms/op
                 getUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 253494
  mean =      3.786 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3277 
    [ 2.500,  5.000) = 243809 
    [ 5.000,  7.500) = 5612 
    [ 7.500, 10.000) = 534 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     10.379 ms/op
     p(99.9900) =     22.587 ms/op
     p(99.9990) =     23.429 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 7.031 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.985 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.711 ±(99.9%) 0.013 ms/op
Iteration   1: 4.737 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.755 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  14.942 ms/op
                 listUser·p0.9999: 18.203 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   2: 4.748 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.693 ms/op
                 listUser·p0.95:   6.652 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  16.098 ms/op
                 listUser·p0.9999: 22.053 ms/op
                 listUser·p1.00:   23.822 ms/op

Iteration   3: 4.640 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   6.349 ms/op
                 listUser·p0.99:   8.364 ms/op
                 listUser·p0.999:  18.940 ms/op
                 listUser·p0.9999: 21.734 ms/op
                 listUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 204050
  mean =      4.708 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 290 
    [ 2.500,  5.000) = 159529 
    [ 5.000,  7.500) = 39277 
    [ 7.500, 10.000) = 4190 
    [10.000, 12.500) = 358 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.726 ms/op
     p(95.0000) =      6.619 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     16.645 ms/op
     p(99.9900) =     21.712 ms/op
     p(99.9990) =     23.746 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.704 ± 2.931  ops/ms
ClientGrpc.existUser                       thrpt       3   9.126 ± 1.117  ops/ms
ClientGrpc.getUser                         thrpt       3   8.583 ± 4.099  ops/ms
ClientGrpc.listUser                        thrpt       3   6.787 ± 0.733  ops/ms
ClientGrpc.createUser                       avgt       3   3.692 ± 0.569   ms/op
ClientGrpc.existUser                        avgt       3   3.517 ± 0.756   ms/op
ClientGrpc.getUser                          avgt       3   3.793 ± 1.425   ms/op
ClientGrpc.listUser                         avgt       3   4.623 ± 0.182   ms/op
ClientGrpc.createUser                     sample  263144   3.645 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.761           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.775           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.548           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.988           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.200           ms/op
ClientGrpc.existUser                      sample  277672   3.457 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.767           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.055           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.367           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.366           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.299           ms/op
ClientGrpc.getUser                        sample  253494   3.786 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.721           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.751           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.718           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.379           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.587           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.462           ms/op
ClientGrpc.listUser                       sample  204050   4.708 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.362           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.530           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.619           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.503           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.645           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.712           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.822           ms/op
