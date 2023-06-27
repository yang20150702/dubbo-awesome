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
# Warmup Iteration   1: 3.552 ops/ms
# Warmup Iteration   2: 8.534 ops/ms
# Warmup Iteration   3: 9.251 ops/ms
Iteration   1: 9.470 ops/ms
Iteration   2: 10.081 ops/ms
Iteration   3: 10.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.949 ±(99.9%) 7.816 ops/ms [Average]
  (min, avg, max) = (9.470, 9.949, 10.296), stdev = 0.428
  CI (99.9%): [2.133, 17.765] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.445 ops/ms
# Warmup Iteration   2: 10.343 ops/ms
# Warmup Iteration   3: 10.884 ops/ms
Iteration   1: 10.874 ops/ms
Iteration   2: 11.091 ops/ms
Iteration   3: 10.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.918 ±(99.9%) 2.849 ops/ms [Average]
  (min, avg, max) = (10.788, 10.918, 11.091), stdev = 0.156
  CI (99.9%): [8.069, 13.767] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.693 ops/ms
# Warmup Iteration   2: 10.103 ops/ms
# Warmup Iteration   3: 10.452 ops/ms
Iteration   1: 10.406 ops/ms
Iteration   2: 10.504 ops/ms
Iteration   3: 10.508 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.472 ±(99.9%) 1.055 ops/ms [Average]
  (min, avg, max) = (10.406, 10.472, 10.508), stdev = 0.058
  CI (99.9%): [9.417, 11.527] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.594 ops/ms
# Warmup Iteration   2: 7.671 ops/ms
# Warmup Iteration   3: 7.738 ops/ms
Iteration   1: 7.945 ops/ms
Iteration   2: 7.937 ops/ms
Iteration   3: 7.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.944 ±(99.9%) 0.124 ops/ms [Average]
  (min, avg, max) = (7.937, 7.944, 7.951), stdev = 0.007
  CI (99.9%): [7.820, 8.069] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.589 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.223 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.005 ms/op
Iteration   1: 3.104 ±(99.9%) 0.002 ms/op
Iteration   2: 3.032 ±(99.9%) 0.003 ms/op
Iteration   3: 3.049 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.061 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (3.032, 3.061, 3.104), stdev = 0.038
  CI (99.9%): [2.377, 3.746] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.115 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.001 ms/op
Iteration   1: 2.925 ±(99.9%) 0.002 ms/op
Iteration   2: 2.908 ±(99.9%) 0.001 ms/op
Iteration   3: 2.876 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.903 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (2.876, 2.903, 2.925), stdev = 0.025
  CI (99.9%): [2.451, 3.355] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.502 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.002 ms/op
Iteration   1: 3.033 ±(99.9%) 0.002 ms/op
Iteration   2: 3.098 ±(99.9%) 0.005 ms/op
Iteration   3: 3.069 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.067 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (3.033, 3.067, 3.098), stdev = 0.033
  CI (99.9%): [2.473, 3.661] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.443 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.016 ms/op
Iteration   1: 4.056 ±(99.9%) 0.012 ms/op
Iteration   2: 4.077 ±(99.9%) 0.008 ms/op
Iteration   3: 4.013 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.049 ±(99.9%) 0.589 ms/op [Average]
  (min, avg, max) = (4.013, 4.049, 4.077), stdev = 0.032
  CI (99.9%): [3.459, 4.638] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.393 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
Iteration   1: 3.076 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.864 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.899 ms/op
                 createUser·p0.99:   4.578 ms/op
                 createUser·p0.999:  12.173 ms/op
                 createUser·p0.9999: 27.119 ms/op
                 createUser·p1.00:   27.853 ms/op

Iteration   2: 3.041 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.712 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  7.786 ms/op
                 createUser·p0.9999: 18.185 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.633 ms/op
                 createUser·p0.99:   4.457 ms/op
                 createUser·p0.999:  11.957 ms/op
                 createUser·p0.9999: 22.544 ms/op
                 createUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314331
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17513 
    [ 2.500,  5.000) = 295000 
    [ 5.000,  7.500) = 1360 
    [ 7.500, 10.000) = 115 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =     11.289 ms/op
     p(99.9900) =     25.975 ms/op
     p(99.9990) =     27.783 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.810 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.992 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.005 ms/op
Iteration   1: 2.873 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.170 ms/op
                 existUser·p0.95:   3.244 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  7.394 ms/op
                 existUser·p0.9999: 19.328 ms/op
                 existUser·p1.00:   19.595 ms/op

Iteration   2: 2.886 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.105 ms/op
                 existUser·p0.9999: 14.842 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   3: 3.036 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.588 ms/op
                 existUser·p0.999:  11.523 ms/op
                 existUser·p0.9999: 19.158 ms/op
                 existUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327783
  mean =      2.930 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1740 
    [ 1.250,  2.500) = 28693 
    [ 2.500,  3.750) = 288331 
    [ 3.750,  5.000) = 7617 
    [ 5.000,  6.250) = 647 
    [ 6.250,  7.500) = 287 
    [ 7.500,  8.750) = 164 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 36 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      8.622 ms/op
     p(99.9900) =     19.144 ms/op
     p(99.9990) =     19.759 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.637 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.008 ms/op
Iteration   1: 3.051 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.903 ms/op
                 getUser·p0.9999: 12.485 ms/op
                 getUser·p1.00:   12.681 ms/op

Iteration   2: 3.051 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.722 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.579 ms/op
                 getUser·p0.9999: 15.052 ms/op
                 getUser·p1.00:   15.352 ms/op

Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.738 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.866 ms/op
                 getUser·p0.9999: 23.380 ms/op
                 getUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314529
  mean =      3.051 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15023 
    [ 2.500,  5.000) = 297996 
    [ 5.000,  7.500) = 1122 
    [ 7.500, 10.000) = 179 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.794 ms/op
     p(99.9900) =     22.595 ms/op
     p(99.9990) =     24.758 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 5.864 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.071 ±(99.9%) 0.012 ms/op
Iteration   1: 4.048 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  13.318 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   2: 3.984 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.636 ms/op
                 listUser·p0.50:   3.815 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  15.446 ms/op
                 listUser·p0.9999: 37.880 ms/op
                 listUser·p1.00:   45.810 ms/op

Iteration   3: 4.150 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  16.181 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236393
  mean =      4.060 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 210316 
    [ 5.000, 10.000) = 25650 
    [10.000, 15.000) = 176 
    [15.000, 20.000) = 205 
    [20.000, 25.000) = 14 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.778 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     15.231 ms/op
     p(99.9900) =     37.814 ms/op
     p(99.9990) =     41.251 ms/op
     p(99.9999) =     45.810 ms/op
    p(100.0000) =     45.810 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.949 ± 7.816  ops/ms
ClientGrpc.existUser                       thrpt       3  10.918 ± 2.849  ops/ms
ClientGrpc.getUser                         thrpt       3  10.472 ± 1.055  ops/ms
ClientGrpc.listUser                        thrpt       3   7.944 ± 0.124  ops/ms
ClientGrpc.createUser                       avgt       3   3.061 ± 0.684   ms/op
ClientGrpc.existUser                        avgt       3   2.903 ± 0.452   ms/op
ClientGrpc.getUser                          avgt       3   3.067 ± 0.594   ms/op
ClientGrpc.listUser                         avgt       3   4.049 ± 0.589   ms/op
ClientGrpc.createUser                     sample  314331   3.052 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.712           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.289           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.975           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.853           ms/op
ClientGrpc.existUser                      sample  327783   2.930 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.546           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.622           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.144           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.792           ms/op
ClientGrpc.getUser                        sample  314529   3.051 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.564           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.498           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.794           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.595           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.936           ms/op
ClientGrpc.listUser                       sample  236393   4.060 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.636           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.778           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.231           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          37.814           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          45.810           ms/op
