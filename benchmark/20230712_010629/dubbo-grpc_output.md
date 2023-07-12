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
# Warmup Iteration   1: 3.041 ops/ms
# Warmup Iteration   2: 6.722 ops/ms
# Warmup Iteration   3: 7.784 ops/ms
Iteration   1: 8.316 ops/ms
Iteration   2: 8.736 ops/ms
Iteration   3: 8.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.569 ±(99.9%) 4.063 ops/ms [Average]
  (min, avg, max) = (8.316, 8.569, 8.736), stdev = 0.223
  CI (99.9%): [4.506, 12.632] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.689 ops/ms
# Warmup Iteration   2: 8.577 ops/ms
# Warmup Iteration   3: 8.974 ops/ms
Iteration   1: 9.358 ops/ms
Iteration   2: 8.999 ops/ms
Iteration   3: 9.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.239 ±(99.9%) 3.798 ops/ms [Average]
  (min, avg, max) = (8.999, 9.239, 9.360), stdev = 0.208
  CI (99.9%): [5.441, 13.037] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.283 ops/ms
# Warmup Iteration   2: 8.251 ops/ms
# Warmup Iteration   3: 8.416 ops/ms
Iteration   1: 8.645 ops/ms
Iteration   2: 8.883 ops/ms
Iteration   3: 8.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.734 ±(99.9%) 2.371 ops/ms [Average]
  (min, avg, max) = (8.645, 8.734, 8.883), stdev = 0.130
  CI (99.9%): [6.362, 11.105] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.486 ops/ms
# Warmup Iteration   2: 6.414 ops/ms
# Warmup Iteration   3: 6.683 ops/ms
Iteration   1: 6.542 ops/ms
Iteration   2: 6.798 ops/ms
Iteration   3: 6.824 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.721 ±(99.9%) 2.848 ops/ms [Average]
  (min, avg, max) = (6.542, 6.721, 6.824), stdev = 0.156
  CI (99.9%): [3.873, 9.570] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.405 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.792 ±(99.9%) 0.006 ms/op
Iteration   1: 3.760 ±(99.9%) 0.004 ms/op
Iteration   2: 3.690 ±(99.9%) 0.004 ms/op
Iteration   3: 3.708 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.720 ±(99.9%) 0.666 ms/op [Average]
  (min, avg, max) = (3.690, 3.720, 3.760), stdev = 0.036
  CI (99.9%): [3.054, 4.385] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.964 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.004 ms/op
Iteration   1: 3.441 ±(99.9%) 0.003 ms/op
Iteration   2: 3.426 ±(99.9%) 0.004 ms/op
Iteration   3: 3.387 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.418 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (3.387, 3.418, 3.441), stdev = 0.028
  CI (99.9%): [2.912, 3.923] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.305 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.736 ±(99.9%) 0.004 ms/op
Iteration   1: 3.631 ±(99.9%) 0.005 ms/op
Iteration   2: 3.586 ±(99.9%) 0.006 ms/op
Iteration   3: 3.622 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.613 ±(99.9%) 0.435 ms/op [Average]
  (min, avg, max) = (3.586, 3.613, 3.631), stdev = 0.024
  CI (99.9%): [3.178, 4.048] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.229 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 5.214 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.880 ±(99.9%) 0.025 ms/op
Iteration   1: 4.531 ±(99.9%) 0.007 ms/op
Iteration   2: 4.774 ±(99.9%) 0.012 ms/op
Iteration   3: 4.900 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.735 ±(99.9%) 3.428 ms/op [Average]
  (min, avg, max) = (4.531, 4.735, 4.900), stdev = 0.188
  CI (99.9%): [1.307, 8.163] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.447 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.889 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.775 ±(99.9%) 0.010 ms/op
Iteration   1: 3.627 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.361 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  10.349 ms/op
                 createUser·p0.9999: 25.270 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   2: 3.758 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.757 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.750 ms/op
                 createUser·p0.999:  18.711 ms/op
                 createUser·p0.9999: 25.034 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   3: 3.728 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.611 ms/op
                 createUser·p0.999:  12.643 ms/op
                 createUser·p0.9999: 24.688 ms/op
                 createUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259186
  mean =      3.704 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12466 
    [ 2.500,  5.000) = 236112 
    [ 5.000,  7.500) = 9149 
    [ 7.500, 10.000) = 1096 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.361 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     11.633 ms/op
     p(99.9900) =     25.035 ms/op
     p(99.9990) =     25.790 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.532 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.010 ms/op
Iteration   1: 3.514 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  9.339 ms/op
                 existUser·p0.9999: 25.451 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   2: 3.557 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   3.473 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.604 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  11.667 ms/op
                 existUser·p0.9999: 19.202 ms/op
                 existUser·p1.00:   19.726 ms/op

Iteration   3: 3.552 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   3.457 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.488 ms/op
                 existUser·p0.999:  14.123 ms/op
                 existUser·p0.9999: 31.686 ms/op
                 existUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270951
  mean =      3.541 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8378 
    [ 2.500,  5.000) = 254835 
    [ 5.000,  7.500) = 6387 
    [ 7.500, 10.000) = 924 
    [10.000, 12.500) = 191 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     11.911 ms/op
     p(99.9900) =     31.195 ms/op
     p(99.9990) =     32.493 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.465 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.741 ±(99.9%) 0.010 ms/op
Iteration   1: 3.725 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  11.362 ms/op
                 getUser·p0.9999: 16.225 ms/op
                 getUser·p1.00:   16.761 ms/op

Iteration   2: 3.792 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   6.513 ms/op
                 getUser·p0.999:  10.584 ms/op
                 getUser·p0.9999: 17.105 ms/op
                 getUser·p1.00:   17.564 ms/op

Iteration   3: 3.681 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.981 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  11.405 ms/op
                 getUser·p0.9999: 21.506 ms/op
                 getUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 257064
  mean =      3.732 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7511 
    [ 2.500,  5.000) = 238063 
    [ 5.000,  7.500) = 9967 
    [ 7.500, 10.000) = 1113 
    [10.000, 12.500) = 232 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     11.141 ms/op
     p(99.9900) =     21.178 ms/op
     p(99.9990) =     21.955 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 6.624 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.103 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.892 ±(99.9%) 0.016 ms/op
Iteration   1: 4.813 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   6.291 ms/op
                 listUser·p0.95:   7.209 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  16.621 ms/op
                 listUser·p0.9999: 22.130 ms/op
                 listUser·p1.00:   23.691 ms/op

Iteration   2: 4.759 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.964 ms/op
                 listUser·p0.95:   6.709 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  16.332 ms/op
                 listUser·p0.9999: 19.850 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   3: 4.713 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.890 ms/op
                 listUser·p0.95:   6.816 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  21.329 ms/op
                 listUser·p0.9999: 31.167 ms/op
                 listUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201557
  mean =      4.761 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 514 
    [ 2.500,  5.000) = 153051 
    [ 5.000,  7.500) = 41793 
    [ 7.500, 10.000) = 5070 
    [10.000, 12.500) = 634 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.842 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      6.046 ms/op
     p(95.0000) =      6.930 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     17.039 ms/op
     p(99.9900) =     29.584 ms/op
     p(99.9990) =     31.980 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.569 ± 4.063  ops/ms
ClientGrpc.existUser                       thrpt       3   9.239 ± 3.798  ops/ms
ClientGrpc.getUser                         thrpt       3   8.734 ± 2.371  ops/ms
ClientGrpc.listUser                        thrpt       3   6.721 ± 2.848  ops/ms
ClientGrpc.createUser                       avgt       3   3.720 ± 0.666   ms/op
ClientGrpc.existUser                        avgt       3   3.418 ± 0.505   ms/op
ClientGrpc.getUser                          avgt       3   3.613 ± 0.435   ms/op
ClientGrpc.listUser                         avgt       3   4.735 ± 3.428   ms/op
ClientGrpc.createUser                     sample  259186   3.704 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.361           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.545           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.633           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.035           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.083           ms/op
ClientGrpc.existUser                      sample  270951   3.541 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.721           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.250           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.911           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.195           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.194           ms/op
ClientGrpc.getUser                        sample  257064   3.732 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.974           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.915           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.693           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.141           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.178           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.053           ms/op
ClientGrpc.listUser                       sample  201557   4.761 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.842           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.011           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.039           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.584           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.080           ms/op
