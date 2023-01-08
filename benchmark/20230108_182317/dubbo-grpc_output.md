# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.244 ops/ms
# Warmup Iteration   2: 7.068 ops/ms
# Warmup Iteration   3: 8.024 ops/ms
Iteration   1: 8.285 ops/ms
Iteration   2: 8.290 ops/ms
Iteration   3: 8.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.278 ±(99.9%) 0.300 ops/ms [Average]
  (min, avg, max) = (8.259, 8.278, 8.290), stdev = 0.016
  CI (99.9%): [7.977, 8.578] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.981 ops/ms
# Warmup Iteration   2: 8.493 ops/ms
# Warmup Iteration   3: 8.595 ops/ms
Iteration   1: 8.804 ops/ms
Iteration   2: 9.047 ops/ms
Iteration   3: 8.739 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.863 ±(99.9%) 2.965 ops/ms [Average]
  (min, avg, max) = (8.739, 8.863, 9.047), stdev = 0.162
  CI (99.9%): [5.898, 11.828] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.588 ops/ms
# Warmup Iteration   2: 7.882 ops/ms
# Warmup Iteration   3: 8.316 ops/ms
Iteration   1: 8.247 ops/ms
Iteration   2: 8.361 ops/ms
Iteration   3: 8.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.282 ±(99.9%) 1.251 ops/ms [Average]
  (min, avg, max) = (8.238, 8.282, 8.361), stdev = 0.069
  CI (99.9%): [7.031, 9.533] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.167 ops/ms
# Warmup Iteration   2: 5.980 ops/ms
# Warmup Iteration   3: 6.500 ops/ms
Iteration   1: 6.532 ops/ms
Iteration   2: 6.492 ops/ms
Iteration   3: 6.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.561 ±(99.9%) 1.581 ops/ms [Average]
  (min, avg, max) = (6.492, 6.561, 6.658), stdev = 0.087
  CI (99.9%): [4.980, 8.142] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.485 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.112 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.003 ms/op
Iteration   1: 3.923 ±(99.9%) 0.005 ms/op
Iteration   2: 3.831 ±(99.9%) 0.002 ms/op
Iteration   3: 3.943 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.899 ±(99.9%) 1.094 ms/op [Average]
  (min, avg, max) = (3.831, 3.899, 3.943), stdev = 0.060
  CI (99.9%): [2.805, 4.994] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.047 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.813 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.728 ±(99.9%) 0.003 ms/op
Iteration   1: 3.692 ±(99.9%) 0.003 ms/op
Iteration   2: 3.658 ±(99.9%) 0.003 ms/op
Iteration   3: 3.591 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.647 ±(99.9%) 0.932 ms/op [Average]
  (min, avg, max) = (3.591, 3.647, 3.692), stdev = 0.051
  CI (99.9%): [2.715, 4.579] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.426 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.854 ±(99.9%) 0.002 ms/op
Iteration   1: 3.902 ±(99.9%) 0.003 ms/op
Iteration   2: 3.836 ±(99.9%) 0.004 ms/op
Iteration   3: 3.810 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.849 ±(99.9%) 0.864 ms/op [Average]
  (min, avg, max) = (3.810, 3.849, 3.902), stdev = 0.047
  CI (99.9%): [2.986, 4.713] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.362 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.338 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.963 ±(99.9%) 0.017 ms/op
Iteration   1: 4.795 ±(99.9%) 0.009 ms/op
Iteration   2: 4.736 ±(99.9%) 0.014 ms/op
Iteration   3: 4.917 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.816 ±(99.9%) 1.680 ms/op [Average]
  (min, avg, max) = (4.736, 4.816, 4.917), stdev = 0.092
  CI (99.9%): [3.136, 6.496] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.106 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.013 ms/op
Iteration   1: 3.790 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.653 ms/op
                 createUser·p0.95:   5.194 ms/op
                 createUser·p0.99:   7.815 ms/op
                 createUser·p0.999:  12.019 ms/op
                 createUser·p0.9999: 19.501 ms/op
                 createUser·p1.00:   19.923 ms/op

Iteration   2: 3.860 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   6.586 ms/op
                 createUser·p0.999:  16.980 ms/op
                 createUser·p0.9999: 22.311 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   3: 3.761 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.504 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   5.112 ms/op
                 createUser·p0.99:   7.135 ms/op
                 createUser·p0.999:  11.274 ms/op
                 createUser·p0.9999: 27.165 ms/op
                 createUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 252166
  mean =      3.803 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9830 
    [ 2.500,  5.000) = 227261 
    [ 5.000,  7.500) = 12848 
    [ 7.500, 10.000) = 1736 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      5.120 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     11.990 ms/op
     p(99.9900) =     26.717 ms/op
     p(99.9990) =     27.524 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.359 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.011 ms/op
Iteration   1: 3.634 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.522 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  10.912 ms/op
                 existUser·p0.9999: 14.801 ms/op
                 existUser·p1.00:   17.236 ms/op

Iteration   2: 3.714 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   3.621 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   6.884 ms/op
                 existUser·p0.999:  11.594 ms/op
                 existUser·p0.9999: 18.264 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   3: 3.665 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.878 ms/op
                 existUser·p0.50:   3.592 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   6.684 ms/op
                 existUser·p0.999:  11.169 ms/op
                 existUser·p0.9999: 19.833 ms/op
                 existUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 261470
  mean =      3.671 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11991 
    [ 2.500,  5.000) = 238434 
    [ 5.000,  7.500) = 9419 
    [ 7.500, 10.000) = 1216 
    [10.000, 12.500) = 257 
    [12.500, 15.000) = 54 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     11.150 ms/op
     p(99.9900) =     19.427 ms/op
     p(99.9990) =     20.067 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.298 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.839 ±(99.9%) 0.010 ms/op
Iteration   1: 3.781 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.571 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  11.534 ms/op
                 getUser·p0.9999: 15.231 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   2: 3.852 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.744 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  10.845 ms/op
                 getUser·p0.9999: 16.282 ms/op
                 getUser·p1.00:   16.777 ms/op

Iteration   3: 3.813 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.140 ms/op
                 getUser·p0.999:  10.769 ms/op
                 getUser·p0.9999: 32.735 ms/op
                 getUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251578
  mean =      3.815 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7114 
    [ 2.500,  5.000) = 231739 
    [ 5.000,  7.500) = 11354 
    [ 7.500, 10.000) = 973 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.975 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     10.984 ms/op
     p(99.9900) =     31.326 ms/op
     p(99.9990) =     33.419 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.338 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.171 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.920 ±(99.9%) 0.016 ms/op
Iteration   1: 4.903 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.365 ms/op
                 listUser·p0.95:   7.135 ms/op
                 listUser·p0.99:   9.172 ms/op
                 listUser·p0.999:  15.206 ms/op
                 listUser·p0.9999: 21.708 ms/op
                 listUser·p1.00:   22.184 ms/op

Iteration   2: 4.872 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.250 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  18.177 ms/op
                 listUser·p0.9999: 23.509 ms/op
                 listUser·p1.00:   24.019 ms/op

Iteration   3: 4.990 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.120 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.619 ms/op
                 listUser·p0.95:   7.438 ms/op
                 listUser·p0.99:   9.290 ms/op
                 listUser·p0.999:  19.757 ms/op
                 listUser·p0.9999: 34.669 ms/op
                 listUser·p1.00:   35.258 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 195025
  mean =      4.921 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 470 
    [ 2.500,  5.000) = 132540 
    [ 5.000,  7.500) = 54475 
    [ 7.500, 10.000) = 6477 
    [10.000, 12.500) = 580 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      4.653 ms/op
     p(90.0000) =      6.406 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     18.121 ms/op
     p(99.9900) =     29.426 ms/op
     p(99.9990) =     35.196 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.278 ± 0.300  ops/ms
ClientGrpc.existUser                       thrpt       3   8.863 ± 2.965  ops/ms
ClientGrpc.getUser                         thrpt       3   8.282 ± 1.251  ops/ms
ClientGrpc.listUser                        thrpt       3   6.561 ± 1.581  ops/ms
ClientGrpc.createUser                       avgt       3   3.899 ± 1.094   ms/op
ClientGrpc.existUser                        avgt       3   3.647 ± 0.932   ms/op
ClientGrpc.getUser                          avgt       3   3.849 ± 0.864   ms/op
ClientGrpc.listUser                         avgt       3   4.816 ± 1.680   ms/op
ClientGrpc.createUser                     sample  252166   3.803 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.504           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.120           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.234           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.990           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.717           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.623           ms/op
ClientGrpc.existUser                      sample  261470   3.671 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.577           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.891           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.660           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.150           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.427           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.479           ms/op
ClientGrpc.getUser                        sample  251578   3.815 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.975           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.472           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.984           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.326           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.686           ms/op
ClientGrpc.listUser                       sample  195025   4.921 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.120           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.653           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.406           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.217           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.110           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.121           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.426           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.258           ms/op
