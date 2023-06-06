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
# Warmup Iteration   1: 5.013 ops/ms
# Warmup Iteration   2: 8.866 ops/ms
# Warmup Iteration   3: 10.407 ops/ms
Iteration   1: 10.389 ops/ms
Iteration   2: 10.691 ops/ms
Iteration   3: 10.595 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.559 ±(99.9%) 2.814 ops/ms [Average]
  (min, avg, max) = (10.389, 10.559, 10.691), stdev = 0.154
  CI (99.9%): [7.745, 13.372] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.834 ops/ms
# Warmup Iteration   2: 10.892 ops/ms
# Warmup Iteration   3: 11.427 ops/ms
Iteration   1: 11.329 ops/ms
Iteration   2: 11.236 ops/ms
Iteration   3: 11.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.248 ±(99.9%) 1.378 ops/ms [Average]
  (min, avg, max) = (11.180, 11.248, 11.329), stdev = 0.076
  CI (99.9%): [9.870, 12.626] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.129 ops/ms
# Warmup Iteration   2: 10.397 ops/ms
# Warmup Iteration   3: 10.654 ops/ms
Iteration   1: 10.701 ops/ms
Iteration   2: 10.683 ops/ms
Iteration   3: 10.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.669 ±(99.9%) 0.759 ops/ms [Average]
  (min, avg, max) = (10.622, 10.669, 10.701), stdev = 0.042
  CI (99.9%): [9.910, 11.427] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.072 ops/ms
# Warmup Iteration   2: 8.114 ops/ms
# Warmup Iteration   3: 8.355 ops/ms
Iteration   1: 8.419 ops/ms
Iteration   2: 8.515 ops/ms
Iteration   3: 8.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.512 ±(99.9%) 1.676 ops/ms [Average]
  (min, avg, max) = (8.419, 8.512, 8.602), stdev = 0.092
  CI (99.9%): [6.836, 10.187] (assumes normal distribution)


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
# Warmup Iteration   1: 4.022 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.002 ms/op
Iteration   1: 3.149 ±(99.9%) 0.002 ms/op
Iteration   2: 3.035 ±(99.9%) 0.002 ms/op
Iteration   3: 3.037 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.074 ±(99.9%) 1.184 ms/op [Average]
  (min, avg, max) = (3.035, 3.074, 3.149), stdev = 0.065
  CI (99.9%): [1.890, 4.258] (assumes normal distribution)


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
# Warmup Iteration   1: 3.132 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.004 ms/op
Iteration   1: 2.868 ±(99.9%) 0.003 ms/op
Iteration   2: 2.775 ±(99.9%) 0.003 ms/op
Iteration   3: 2.845 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.829 ±(99.9%) 0.881 ms/op [Average]
  (min, avg, max) = (2.775, 2.829, 2.868), stdev = 0.048
  CI (99.9%): [1.948, 3.710] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.907 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.003 ms/op
Iteration   1: 3.022 ±(99.9%) 0.004 ms/op
Iteration   2: 2.983 ±(99.9%) 0.003 ms/op
Iteration   3: 2.989 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.998 ±(99.9%) 0.385 ms/op [Average]
  (min, avg, max) = (2.983, 2.998, 3.022), stdev = 0.021
  CI (99.9%): [2.613, 3.383] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.800 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.927 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.040 ms/op
Iteration   1: 3.835 ±(99.9%) 0.016 ms/op
Iteration   2: 3.807 ±(99.9%) 0.027 ms/op
Iteration   3: 3.790 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.811 ±(99.9%) 0.422 ms/op [Average]
  (min, avg, max) = (3.790, 3.811, 3.835), stdev = 0.023
  CI (99.9%): [3.389, 4.232] (assumes normal distribution)


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
# Warmup Iteration   1: 3.902 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 3.089 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.369 ms/op
                 createUser·p0.999:  6.878 ms/op
                 createUser·p0.9999: 15.532 ms/op
                 createUser·p1.00:   17.695 ms/op

Iteration   2: 2.999 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.672 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  12.829 ms/op
                 createUser·p0.9999: 17.236 ms/op
                 createUser·p1.00:   17.531 ms/op

Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  9.978 ms/op
                 createUser·p0.9999: 18.931 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316745
  mean =      3.032 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25316 
    [ 2.500,  5.000) = 290320 
    [ 5.000,  7.500) = 678 
    [ 7.500, 10.000) = 104 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =     10.265 ms/op
     p(99.9900) =     18.284 ms/op
     p(99.9990) =     20.862 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 3.914 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.949 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.861 ±(99.9%) 0.005 ms/op
Iteration   1: 2.905 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.499 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  5.555 ms/op
                 existUser·p0.9999: 12.091 ms/op
                 existUser·p1.00:   12.485 ms/op

Iteration   2: 2.868 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  8.874 ms/op
                 existUser·p0.9999: 14.087 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   3: 2.797 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.465 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.689 ms/op
                 existUser·p0.9999: 14.494 ms/op
                 existUser·p1.00:   14.828 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336409
  mean =      2.856 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4676 
    [ 1.250,  2.500) = 49259 
    [ 2.500,  3.750) = 272783 
    [ 3.750,  5.000) = 8873 
    [ 5.000,  6.250) = 418 
    [ 6.250,  7.500) = 171 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.465 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      6.599 ms/op
     p(99.9900) =     14.238 ms/op
     p(99.9990) =     14.726 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
Iteration   1: 2.985 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.437 ms/op
                 getUser·p0.9999: 19.113 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   2: 3.000 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  6.889 ms/op
                 getUser·p0.9999: 15.718 ms/op
                 getUser·p1.00:   16.171 ms/op

Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.257 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  6.916 ms/op
                 getUser·p0.9999: 15.869 ms/op
                 getUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319473
  mean =      3.002 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 665 
    [ 1.250,  2.500) = 25963 
    [ 2.500,  3.750) = 276686 
    [ 3.750,  5.000) = 15274 
    [ 5.000,  6.250) = 454 
    [ 6.250,  7.500) = 177 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.257 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.709 ms/op
     p(99.9900) =     18.288 ms/op
     p(99.9990) =     19.294 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 4.860 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.009 ms/op
Iteration   1: 3.843 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  12.626 ms/op
                 listUser·p0.9999: 14.959 ms/op
                 listUser·p1.00:   15.204 ms/op

Iteration   2: 3.874 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.766 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.818 ms/op
                 listUser·p0.9999: 23.191 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   3: 3.833 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.628 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  16.354 ms/op
                 listUser·p0.9999: 29.917 ms/op
                 listUser·p1.00:   30.310 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249459
  mean =      3.850 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5797 
    [ 2.500,  5.000) = 223074 
    [ 5.000,  7.500) = 19363 
    [ 7.500, 10.000) = 757 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     13.427 ms/op
     p(99.9900) =     23.203 ms/op
     p(99.9990) =     30.147 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.559 ± 2.814  ops/ms
ClientGrpc.existUser                       thrpt       3  11.248 ± 1.378  ops/ms
ClientGrpc.getUser                         thrpt       3  10.669 ± 0.759  ops/ms
ClientGrpc.listUser                        thrpt       3   8.512 ± 1.676  ops/ms
ClientGrpc.createUser                       avgt       3   3.074 ± 1.184   ms/op
ClientGrpc.existUser                        avgt       3   2.829 ± 0.881   ms/op
ClientGrpc.getUser                          avgt       3   2.998 ± 0.385   ms/op
ClientGrpc.listUser                         avgt       3   3.811 ± 0.422   ms/op
ClientGrpc.createUser                     sample  316745   3.032 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.657           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.265           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.284           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.234           ms/op
ClientGrpc.existUser                      sample  336409   2.856 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.465           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.599           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.238           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.828           ms/op
ClientGrpc.getUser                        sample  319473   3.002 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.257           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.709           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.288           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.431           ms/op
ClientGrpc.listUser                       sample  249459   3.850 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.628           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.703           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.427           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.203           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.310           ms/op
