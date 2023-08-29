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
# Warmup Iteration   1: 2.241 ops/ms
# Warmup Iteration   2: 5.430 ops/ms
# Warmup Iteration   3: 7.039 ops/ms
Iteration   1: 7.275 ops/ms
Iteration   2: 7.250 ops/ms
Iteration   3: 7.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.242 ±(99.9%) 0.693 ops/ms [Average]
  (min, avg, max) = (7.200, 7.242, 7.275), stdev = 0.038
  CI (99.9%): [6.549, 7.935] (assumes normal distribution)


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
# Warmup Iteration   1: 5.275 ops/ms
# Warmup Iteration   2: 6.945 ops/ms
# Warmup Iteration   3: 7.636 ops/ms
Iteration   1: 7.884 ops/ms
Iteration   2: 7.744 ops/ms
Iteration   3: 7.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.857 ±(99.9%) 1.858 ops/ms [Average]
  (min, avg, max) = (7.744, 7.857, 7.942), stdev = 0.102
  CI (99.9%): [5.999, 9.715] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.419 ops/ms
# Warmup Iteration   2: 6.951 ops/ms
# Warmup Iteration   3: 7.220 ops/ms
Iteration   1: 7.558 ops/ms
Iteration   2: 7.593 ops/ms
Iteration   3: 7.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.516 ±(99.9%) 1.889 ops/ms [Average]
  (min, avg, max) = (7.399, 7.516, 7.593), stdev = 0.104
  CI (99.9%): [5.627, 9.406] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.703 ops/ms
# Warmup Iteration   2: 5.123 ops/ms
# Warmup Iteration   3: 5.514 ops/ms
Iteration   1: 5.687 ops/ms
Iteration   2: 5.881 ops/ms
Iteration   3: 5.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.824 ±(99.9%) 2.166 ops/ms [Average]
  (min, avg, max) = (5.687, 5.824, 5.903), stdev = 0.119
  CI (99.9%): [3.658, 7.989] (assumes normal distribution)


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
# Warmup Iteration   1: 7.589 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.700 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.507 ±(99.9%) 0.005 ms/op
Iteration   1: 4.279 ±(99.9%) 0.006 ms/op
Iteration   2: 4.241 ±(99.9%) 0.003 ms/op
Iteration   3: 4.233 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.251 ±(99.9%) 0.445 ms/op [Average]
  (min, avg, max) = (4.233, 4.251, 4.279), stdev = 0.024
  CI (99.9%): [3.805, 4.696] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.361 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.014 ±(99.9%) 0.004 ms/op
Iteration   1: 3.985 ±(99.9%) 0.003 ms/op
Iteration   2: 3.963 ±(99.9%) 0.009 ms/op
Iteration   3: 4.069 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.005 ±(99.9%) 1.024 ms/op [Average]
  (min, avg, max) = (3.963, 4.005, 4.069), stdev = 0.056
  CI (99.9%): [2.982, 5.029] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.662 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.534 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.312 ±(99.9%) 0.005 ms/op
Iteration   1: 4.398 ±(99.9%) 0.003 ms/op
Iteration   2: 4.234 ±(99.9%) 0.002 ms/op
Iteration   3: 4.122 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.251 ±(99.9%) 2.535 ms/op [Average]
  (min, avg, max) = (4.122, 4.251, 4.398), stdev = 0.139
  CI (99.9%): [1.716, 6.786] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.300 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 6.506 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.591 ±(99.9%) 0.017 ms/op
Iteration   1: 5.431 ±(99.9%) 0.031 ms/op
Iteration   2: 5.571 ±(99.9%) 0.015 ms/op
Iteration   3: 5.399 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.467 ±(99.9%) 1.666 ms/op [Average]
  (min, avg, max) = (5.399, 5.467, 5.571), stdev = 0.091
  CI (99.9%): [3.801, 7.133] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.670 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.575 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.013 ms/op
Iteration   1: 4.328 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   4.194 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.743 ms/op
                 createUser·p0.99:   7.889 ms/op
                 createUser·p0.999:  12.681 ms/op
                 createUser·p0.9999: 31.792 ms/op
                 createUser·p1.00:   32.276 ms/op

Iteration   2: 4.331 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.325 ms/op
                 createUser·p0.95:   5.710 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  11.723 ms/op
                 createUser·p0.9999: 20.697 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   3: 4.231 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   4.121 ms/op
                 createUser·p0.90:   5.218 ms/op
                 createUser·p0.95:   5.661 ms/op
                 createUser·p0.99:   7.274 ms/op
                 createUser·p0.999:  13.194 ms/op
                 createUser·p0.9999: 33.976 ms/op
                 createUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 223432
  mean =      4.296 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2333 
    [ 2.500,  5.000) = 185176 
    [ 5.000,  7.500) = 33763 
    [ 7.500, 10.000) = 1506 
    [10.000, 12.500) = 393 
    [12.500, 15.000) = 131 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.852 ms/op
     p(50.0000) =      4.174 ms/op
     p(90.0000) =      5.292 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     12.822 ms/op
     p(99.9900) =     33.204 ms/op
     p(99.9990) =     34.310 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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
# Warmup Iteration   1: 5.618 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.404 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.011 ms/op
Iteration   1: 4.096 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.471 ms/op
                 existUser·p0.50:   3.973 ms/op
                 existUser·p0.90:   5.202 ms/op
                 existUser·p0.95:   5.685 ms/op
                 existUser·p0.99:   7.811 ms/op
                 existUser·p0.999:  13.286 ms/op
                 existUser·p0.9999: 18.848 ms/op
                 existUser·p1.00:   19.988 ms/op

Iteration   2: 3.981 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   4.923 ms/op
                 existUser·p0.95:   5.399 ms/op
                 existUser·p0.99:   7.414 ms/op
                 existUser·p0.999:  12.596 ms/op
                 existUser·p0.9999: 21.330 ms/op
                 existUser·p1.00:   22.118 ms/op

Iteration   3: 4.081 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   3.949 ms/op
                 existUser·p0.90:   5.202 ms/op
                 existUser·p0.95:   5.759 ms/op
                 existUser·p0.99:   7.803 ms/op
                 existUser·p0.999:  12.807 ms/op
                 existUser·p0.9999: 24.592 ms/op
                 existUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 236698
  mean =      4.052 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9794 
    [ 2.500,  5.000) = 199201 
    [ 5.000,  7.500) = 25054 
    [ 7.500, 10.000) = 2031 
    [10.000, 12.500) = 346 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.471 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      7.684 ms/op
     p(99.9000) =     12.850 ms/op
     p(99.9900) =     23.669 ms/op
     p(99.9990) =     31.278 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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
# Warmup Iteration   1: 6.519 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.707 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.323 ±(99.9%) 0.014 ms/op
Iteration   1: 4.235 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   4.092 ms/op
                 getUser·p0.90:   5.145 ms/op
                 getUser·p0.95:   5.693 ms/op
                 getUser·p0.99:   8.684 ms/op
                 getUser·p0.999:  13.034 ms/op
                 getUser·p0.9999: 21.430 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   2: 4.305 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.394 ms/op
                 getUser·p0.50:   4.186 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   8.012 ms/op
                 getUser·p0.999:  13.822 ms/op
                 getUser·p0.9999: 19.730 ms/op
                 getUser·p1.00:   20.644 ms/op

Iteration   3: 4.188 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   4.080 ms/op
                 getUser·p0.90:   5.128 ms/op
                 getUser·p0.95:   5.595 ms/op
                 getUser·p0.99:   7.466 ms/op
                 getUser·p0.999:  14.118 ms/op
                 getUser·p0.9999: 20.492 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 226316
  mean =      4.242 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4644 
    [ 2.500,  5.000) = 190406 
    [ 5.000,  7.500) = 28402 
    [ 7.500, 10.000) = 1843 
    [10.000, 12.500) = 702 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.394 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     13.714 ms/op
     p(99.9900) =     20.963 ms/op
     p(99.9990) =     21.684 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.819 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 6.183 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.572 ±(99.9%) 0.021 ms/op
Iteration   1: 5.596 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.417 ms/op
                 listUser·p0.50:   5.292 ms/op
                 listUser·p0.90:   7.291 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   11.026 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 20.148 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   2: 5.762 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.427 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   7.733 ms/op
                 listUser·p0.95:   8.815 ms/op
                 listUser·p0.99:   11.551 ms/op
                 listUser·p0.999:  18.890 ms/op
                 listUser·p0.9999: 20.804 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   3: 5.718 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.518 ms/op
                 listUser·p0.50:   5.407 ms/op
                 listUser·p0.90:   7.496 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   11.256 ms/op
                 listUser·p0.999:  22.088 ms/op
                 listUser·p0.9999: 26.411 ms/op
                 listUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168597
  mean =      5.691 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 120 
    [ 2.500,  5.000) = 55986 
    [ 5.000,  7.500) = 95458 
    [ 7.500, 10.000) = 13710 
    [10.000, 12.500) = 2296 
    [12.500, 15.000) = 509 
    [15.000, 17.500) = 264 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      5.366 ms/op
     p(90.0000) =      7.520 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     11.272 ms/op
     p(99.9000) =     19.425 ms/op
     p(99.9900) =     25.203 ms/op
     p(99.9990) =     27.360 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.242 ± 0.693  ops/ms
ClientGrpc.existUser                       thrpt       3   7.857 ± 1.858  ops/ms
ClientGrpc.getUser                         thrpt       3   7.516 ± 1.889  ops/ms
ClientGrpc.listUser                        thrpt       3   5.824 ± 2.166  ops/ms
ClientGrpc.createUser                       avgt       3   4.251 ± 0.445   ms/op
ClientGrpc.existUser                        avgt       3   4.005 ± 1.024   ms/op
ClientGrpc.getUser                          avgt       3   4.251 ± 2.535   ms/op
ClientGrpc.listUser                         avgt       3   5.467 ± 1.666   ms/op
ClientGrpc.createUser                     sample  223432   4.296 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.852           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.174           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.292           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.702           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.430           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.822           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.204           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.996           ms/op
ClientGrpc.existUser                      sample  236698   4.052 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.471           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.936           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.120           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.620           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.684           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.850           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.669           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.425           ms/op
ClientGrpc.getUser                        sample  226316   4.242 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.394           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.116           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.210           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.702           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.086           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.714           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.963           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.495           ms/op
ClientGrpc.listUser                       sample  168597   5.691 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.417           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.520           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.552           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.272           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.425           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.203           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.787           ms/op
