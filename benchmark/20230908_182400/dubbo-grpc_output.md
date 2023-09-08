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
# Warmup Iteration   1: 2.032 ops/ms
# Warmup Iteration   2: 5.025 ops/ms
# Warmup Iteration   3: 6.577 ops/ms
Iteration   1: 6.633 ops/ms
Iteration   2: 6.772 ops/ms
Iteration   3: 6.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.758 ±(99.9%) 2.172 ops/ms [Average]
  (min, avg, max) = (6.633, 6.758, 6.870), stdev = 0.119
  CI (99.9%): [4.586, 8.930] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.120 ops/ms
# Warmup Iteration   2: 6.750 ops/ms
# Warmup Iteration   3: 7.161 ops/ms
Iteration   1: 7.330 ops/ms
Iteration   2: 7.103 ops/ms
Iteration   3: 7.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.251 ±(99.9%) 2.345 ops/ms [Average]
  (min, avg, max) = (7.103, 7.251, 7.330), stdev = 0.129
  CI (99.9%): [4.906, 9.597] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 4.143 ops/ms
# Warmup Iteration   2: 6.117 ops/ms
# Warmup Iteration   3: 6.773 ops/ms
Iteration   1: 6.681 ops/ms
Iteration   2: 6.806 ops/ms
Iteration   3: 6.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.743 ±(99.9%) 1.139 ops/ms [Average]
  (min, avg, max) = (6.681, 6.743, 6.806), stdev = 0.062
  CI (99.9%): [5.604, 7.882] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.185 ops/ms
# Warmup Iteration   2: 4.816 ops/ms
# Warmup Iteration   3: 5.220 ops/ms
Iteration   1: 5.228 ops/ms
Iteration   2: 5.414 ops/ms
Iteration   3: 5.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.331 ±(99.9%) 1.732 ops/ms [Average]
  (min, avg, max) = (5.228, 5.331, 5.414), stdev = 0.095
  CI (99.9%): [3.600, 7.063] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.266 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.015 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.898 ±(99.9%) 0.014 ms/op
Iteration   1: 4.668 ±(99.9%) 0.003 ms/op
Iteration   2: 4.699 ±(99.9%) 0.004 ms/op
Iteration   3: 4.720 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.696 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (4.668, 4.696, 4.720), stdev = 0.026
  CI (99.9%): [4.221, 5.171] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.525 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.904 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.659 ±(99.9%) 0.014 ms/op
Iteration   1: 4.557 ±(99.9%) 0.004 ms/op
Iteration   2: 4.522 ±(99.9%) 0.006 ms/op
Iteration   3: 4.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.522 ±(99.9%) 0.660 ms/op [Average]
  (min, avg, max) = (4.485, 4.522, 4.557), stdev = 0.036
  CI (99.9%): [3.862, 5.181] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.357 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.165 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.836 ±(99.9%) 0.008 ms/op
Iteration   1: 4.655 ±(99.9%) 0.007 ms/op
Iteration   2: 4.639 ±(99.9%) 0.014 ms/op
Iteration   3: 4.579 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.624 ±(99.9%) 0.728 ms/op [Average]
  (min, avg, max) = (4.579, 4.624, 4.655), stdev = 0.040
  CI (99.9%): [3.896, 5.353] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.053 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 6.706 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 6.210 ±(99.9%) 0.013 ms/op
Iteration   1: 6.159 ±(99.9%) 0.028 ms/op
Iteration   2: 6.081 ±(99.9%) 0.029 ms/op
Iteration   3: 6.026 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.088 ±(99.9%) 1.218 ms/op [Average]
  (min, avg, max) = (6.026, 6.088, 6.159), stdev = 0.067
  CI (99.9%): [4.870, 7.307] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.613 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 5.084 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.845 ±(99.9%) 0.017 ms/op
Iteration   1: 4.740 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   4.514 ms/op
                 createUser·p0.90:   6.013 ms/op
                 createUser·p0.95:   6.644 ms/op
                 createUser·p0.99:   9.519 ms/op
                 createUser·p0.999:  13.658 ms/op
                 createUser·p0.9999: 18.612 ms/op
                 createUser·p1.00:   20.120 ms/op

Iteration   2: 4.715 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   4.547 ms/op
                 createUser·p0.90:   5.988 ms/op
                 createUser·p0.95:   6.586 ms/op
                 createUser·p0.99:   8.847 ms/op
                 createUser·p0.999:  16.226 ms/op
                 createUser·p0.9999: 25.246 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   3: 4.628 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.081 ms/op
                 createUser·p0.50:   4.448 ms/op
                 createUser·p0.90:   5.833 ms/op
                 createUser·p0.95:   6.463 ms/op
                 createUser·p0.99:   9.325 ms/op
                 createUser·p0.999:  18.404 ms/op
                 createUser·p0.9999: 29.667 ms/op
                 createUser·p1.00:   30.605 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 204370
  mean =      4.694 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3278 
    [ 2.500,  5.000) = 140724 
    [ 5.000,  7.500) = 55290 
    [ 7.500, 10.000) = 3675 
    [10.000, 12.500) = 1008 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.956 ms/op
     p(95.0000) =      6.570 ms/op
     p(99.0000) =      9.208 ms/op
     p(99.9000) =     15.985 ms/op
     p(99.9900) =     22.061 ms/op
     p(99.9990) =     30.555 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.642 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.813 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.498 ±(99.9%) 0.014 ms/op
Iteration   1: 4.373 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   4.227 ms/op
                 existUser·p0.90:   5.489 ms/op
                 existUser·p0.95:   5.988 ms/op
                 existUser·p0.99:   8.151 ms/op
                 existUser·p0.999:  12.447 ms/op
                 existUser·p0.9999: 17.140 ms/op
                 existUser·p1.00:   17.924 ms/op

Iteration   2: 4.496 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   4.342 ms/op
                 existUser·p0.90:   5.636 ms/op
                 existUser·p0.95:   6.218 ms/op
                 existUser·p0.99:   8.282 ms/op
                 existUser·p0.999:  14.434 ms/op
                 existUser·p0.9999: 32.819 ms/op
                 existUser·p1.00:   33.522 ms/op

Iteration   3: 4.536 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   4.383 ms/op
                 existUser·p0.90:   5.743 ms/op
                 existUser·p0.95:   6.373 ms/op
                 existUser·p0.99:   8.102 ms/op
                 existUser·p0.999:  11.174 ms/op
                 existUser·p0.9999: 21.950 ms/op
                 existUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 214688
  mean =      4.467 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4872 
    [ 2.500,  5.000) = 160228 
    [ 5.000,  7.500) = 46334 
    [ 7.500, 10.000) = 2527 
    [10.000, 12.500) = 489 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      8.167 ms/op
     p(99.9000) =     12.747 ms/op
     p(99.9900) =     30.904 ms/op
     p(99.9990) =     33.450 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.531 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.065 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.914 ±(99.9%) 0.016 ms/op
Iteration   1: 4.663 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.309 ms/op
                 getUser·p0.50:   4.522 ms/op
                 getUser·p0.90:   6.013 ms/op
                 getUser·p0.95:   6.562 ms/op
                 getUser·p0.99:   8.733 ms/op
                 getUser·p0.999:  13.638 ms/op
                 getUser·p0.9999: 17.091 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   2: 4.798 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   4.620 ms/op
                 getUser·p0.90:   6.087 ms/op
                 getUser·p0.95:   6.783 ms/op
                 getUser·p0.99:   9.421 ms/op
                 getUser·p0.999:  12.911 ms/op
                 getUser·p0.9999: 21.102 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   3: 4.785 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   4.628 ms/op
                 getUser·p0.90:   6.087 ms/op
                 getUser·p0.95:   6.652 ms/op
                 getUser·p0.99:   8.667 ms/op
                 getUser·p0.999:  11.901 ms/op
                 getUser·p0.9999: 19.988 ms/op
                 getUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 202192
  mean =      4.748 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3903 
    [ 2.500,  5.000) = 130663 
    [ 5.000,  7.500) = 62737 
    [ 7.500, 10.000) = 3805 
    [10.000, 12.500) = 843 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      6.062 ms/op
     p(95.0000) =      6.660 ms/op
     p(99.0000) =      8.929 ms/op
     p(99.9000) =     12.826 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     21.722 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 9.100 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 6.518 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 6.190 ±(99.9%) 0.030 ms/op
Iteration   1: 5.936 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   8.102 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   11.829 ms/op
                 listUser·p0.999:  24.741 ms/op
                 listUser·p0.9999: 29.334 ms/op
                 listUser·p1.00:   29.917 ms/op

Iteration   2: 6.088 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   5.702 ms/op
                 listUser·p0.90:   8.012 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   12.059 ms/op
                 listUser·p0.999:  27.394 ms/op
                 listUser·p0.9999: 29.721 ms/op
                 listUser·p1.00:   32.965 ms/op

Iteration   3: 5.953 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   7.946 ms/op
                 listUser·p0.95:   9.093 ms/op
                 listUser·p0.99:   11.747 ms/op
                 listUser·p0.999:  27.492 ms/op
                 listUser·p0.9999: 33.525 ms/op
                 listUser·p1.00:   35.586 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 160246
  mean =      5.992 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 94 
    [ 2.500,  5.000) = 40750 
    [ 5.000,  7.500) = 97382 
    [ 7.500, 10.000) = 17196 
    [10.000, 12.500) = 3640 
    [12.500, 15.000) = 747 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 77 
    [27.500, 30.000) = 88 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      5.603 ms/op
     p(90.0000) =      8.028 ms/op
     p(95.0000) =      9.159 ms/op
     p(99.0000) =     11.878 ms/op
     p(99.9000) =     26.362 ms/op
     p(99.9900) =     31.523 ms/op
     p(99.9990) =     34.638 ms/op
     p(99.9999) =     35.586 ms/op
    p(100.0000) =     35.586 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.758 ± 2.172  ops/ms
ClientGrpc.existUser                       thrpt       3   7.251 ± 2.345  ops/ms
ClientGrpc.getUser                         thrpt       3   6.743 ± 1.139  ops/ms
ClientGrpc.listUser                        thrpt       3   5.331 ± 1.732  ops/ms
ClientGrpc.createUser                       avgt       3   4.696 ± 0.475   ms/op
ClientGrpc.existUser                        avgt       3   4.522 ± 0.660   ms/op
ClientGrpc.getUser                          avgt       3   4.624 ± 0.728   ms/op
ClientGrpc.listUser                         avgt       3   6.088 ± 1.218   ms/op
ClientGrpc.createUser                     sample  204370   4.694 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.952           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.956           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.570           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.208           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.985           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.061           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.605           ms/op
ClientGrpc.existUser                      sample  214688   4.467 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.945           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.620           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.185           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.167           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.747           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.904           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.522           ms/op
ClientGrpc.getUser                        sample  202192   4.748 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.149           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.062           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.660           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.929           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.826           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.709           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.725           ms/op
ClientGrpc.listUser                       sample  160246   5.992 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.249           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.028           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.159           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.878           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          26.362           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.523           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.586           ms/op
