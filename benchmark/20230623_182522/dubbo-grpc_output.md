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
# Warmup Iteration   1: 3.209 ops/ms
# Warmup Iteration   2: 6.811 ops/ms
# Warmup Iteration   3: 7.981 ops/ms
Iteration   1: 8.406 ops/ms
Iteration   2: 8.316 ops/ms
Iteration   3: 8.611 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.444 ±(99.9%) 2.765 ops/ms [Average]
  (min, avg, max) = (8.316, 8.444, 8.611), stdev = 0.152
  CI (99.9%): [5.679, 11.209] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.937 ops/ms
# Warmup Iteration   2: 8.329 ops/ms
# Warmup Iteration   3: 8.675 ops/ms
Iteration   1: 9.013 ops/ms
Iteration   2: 9.540 ops/ms
Iteration   3: 8.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.181 ±(99.9%) 5.681 ops/ms [Average]
  (min, avg, max) = (8.989, 9.181, 9.540), stdev = 0.311
  CI (99.9%): [3.499, 14.862] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.281 ops/ms
# Warmup Iteration   2: 8.165 ops/ms
# Warmup Iteration   3: 8.423 ops/ms
Iteration   1: 8.587 ops/ms
Iteration   2: 8.756 ops/ms
Iteration   3: 8.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.648 ±(99.9%) 1.710 ops/ms [Average]
  (min, avg, max) = (8.587, 8.648, 8.756), stdev = 0.094
  CI (99.9%): [6.938, 10.358] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.333 ops/ms
# Warmup Iteration   2: 6.259 ops/ms
# Warmup Iteration   3: 6.445 ops/ms
Iteration   1: 6.590 ops/ms
Iteration   2: 6.352 ops/ms
Iteration   3: 6.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.524 ±(99.9%) 2.743 ops/ms [Average]
  (min, avg, max) = (6.352, 6.524, 6.631), stdev = 0.150
  CI (99.9%): [3.781, 9.268] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.266 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.732 ±(99.9%) 0.009 ms/op
Iteration   1: 3.784 ±(99.9%) 0.004 ms/op
Iteration   2: 3.745 ±(99.9%) 0.004 ms/op
Iteration   3: 3.693 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.741 ±(99.9%) 0.829 ms/op [Average]
  (min, avg, max) = (3.693, 3.741, 3.784), stdev = 0.045
  CI (99.9%): [2.912, 4.570] (assumes normal distribution)


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
# Warmup Iteration   1: 4.837 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.821 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.006 ms/op
Iteration   1: 3.574 ±(99.9%) 0.004 ms/op
Iteration   2: 3.559 ±(99.9%) 0.003 ms/op
Iteration   3: 3.521 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.551 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (3.521, 3.551, 3.574), stdev = 0.027
  CI (99.9%): [3.055, 4.048] (assumes normal distribution)


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
# Warmup Iteration   1: 5.415 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.009 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.750 ±(99.9%) 0.004 ms/op
Iteration   1: 3.827 ±(99.9%) 0.004 ms/op
Iteration   2: 3.823 ±(99.9%) 0.005 ms/op
Iteration   3: 3.767 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.806 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (3.767, 3.806, 3.827), stdev = 0.034
  CI (99.9%): [3.189, 4.422] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.949 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.227 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.912 ±(99.9%) 0.014 ms/op
Iteration   1: 4.964 ±(99.9%) 0.013 ms/op
Iteration   2: 4.892 ±(99.9%) 0.013 ms/op
Iteration   3: 4.927 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.928 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (4.892, 4.928, 4.964), stdev = 0.036
  CI (99.9%): [4.270, 5.585] (assumes normal distribution)


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
# Warmup Iteration   1: 5.646 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.740 ±(99.9%) 0.010 ms/op
Iteration   1: 3.816 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.120 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   6.871 ms/op
                 createUser·p0.999:  12.215 ms/op
                 createUser·p0.9999: 23.351 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 3.838 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   3.744 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   7.394 ms/op
                 createUser·p0.999:  13.320 ms/op
                 createUser·p0.9999: 17.356 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   3: 3.748 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   3.686 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  9.093 ms/op
                 createUser·p0.9999: 19.857 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 252499
  mean =      3.800 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9536 
    [ 2.500,  5.000) = 230391 
    [ 5.000,  7.500) = 11036 
    [ 7.500, 10.000) = 1124 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     12.009 ms/op
     p(99.9900) =     22.938 ms/op
     p(99.9990) =     23.526 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.104 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.852 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.008 ms/op
Iteration   1: 3.544 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.890 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.530 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  9.547 ms/op
                 existUser·p0.9999: 15.646 ms/op
                 existUser·p1.00:   16.138 ms/op

Iteration   2: 3.442 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.063 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  13.338 ms/op
                 existUser·p0.9999: 23.780 ms/op
                 existUser·p1.00:   24.084 ms/op

Iteration   3: 3.601 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.782 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  13.763 ms/op
                 existUser·p0.9999: 20.979 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 272018
  mean =      3.528 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15228 
    [ 2.500,  5.000) = 250080 
    [ 5.000,  7.500) = 5599 
    [ 7.500, 10.000) = 573 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 231 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.133 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     24.005 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


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
# Warmup Iteration   1: 5.466 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.714 ±(99.9%) 0.010 ms/op
Iteration   1: 3.784 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  10.056 ms/op
                 getUser·p0.9999: 14.993 ms/op
                 getUser·p1.00:   15.876 ms/op

Iteration   2: 3.749 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   5.857 ms/op
                 getUser·p0.999:  8.765 ms/op
                 getUser·p0.9999: 17.037 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   3: 3.799 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.043 ms/op
                 getUser·p0.50:   3.723 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  10.598 ms/op
                 getUser·p0.9999: 18.350 ms/op
                 getUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 254090
  mean =      3.777 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 7497 
    [ 2.500,  3.750) = 127948 
    [ 3.750,  5.000) = 108537 
    [ 5.000,  6.250) = 7644 
    [ 6.250,  7.500) = 1253 
    [ 7.500,  8.750) = 651 
    [ 8.750, 10.000) = 249 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 40 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =      9.911 ms/op
     p(99.9900) =     17.564 ms/op
     p(99.9990) =     19.084 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 7.096 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.274 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 4.952 ±(99.9%) 0.015 ms/op
Iteration   1: 4.913 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.827 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.128 ms/op
                 listUser·p0.95:   7.152 ms/op
                 listUser·p0.99:   9.503 ms/op
                 listUser·p0.999:  15.071 ms/op
                 listUser·p0.9999: 19.382 ms/op
                 listUser·p1.00:   19.694 ms/op

Iteration   2: 4.830 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.430 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.038 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  15.696 ms/op
                 listUser·p0.9999: 18.794 ms/op
                 listUser·p1.00:   20.644 ms/op

Iteration   3: 4.853 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.043 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   6.922 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  20.218 ms/op
                 listUser·p0.9999: 24.052 ms/op
                 listUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197290
  mean =      4.865 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 338 
    [ 2.500,  5.000) = 139678 
    [ 5.000,  7.500) = 50499 
    [ 7.500, 10.000) = 5805 
    [10.000, 12.500) = 598 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.087 ms/op
     p(95.0000) =      7.021 ms/op
     p(99.0000) =      9.028 ms/op
     p(99.9000) =     15.691 ms/op
     p(99.9900) =     23.471 ms/op
     p(99.9990) =     24.185 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.444 ± 2.765  ops/ms
ClientGrpc.existUser                       thrpt       3   9.181 ± 5.681  ops/ms
ClientGrpc.getUser                         thrpt       3   8.648 ± 1.710  ops/ms
ClientGrpc.listUser                        thrpt       3   6.524 ± 2.743  ops/ms
ClientGrpc.createUser                       avgt       3   3.741 ± 0.829   ms/op
ClientGrpc.existUser                        avgt       3   3.551 ± 0.497   ms/op
ClientGrpc.getUser                          avgt       3   3.806 ± 0.617   ms/op
ClientGrpc.listUser                         avgt       3   4.928 ± 0.658   ms/op
ClientGrpc.createUser                     sample  252499   3.800 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.823           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.997           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.726           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.009           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.938           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.593           ms/op
ClientGrpc.existUser                      sample  272018   3.528 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.705           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.956           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.582           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.184           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.084           ms/op
ClientGrpc.getUser                        sample  254090   3.777 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.818           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.882           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.185           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.911           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.564           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.562           ms/op
ClientGrpc.listUser                       sample  197290   4.865 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.043           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.028           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.691           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.471           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.248           ms/op
