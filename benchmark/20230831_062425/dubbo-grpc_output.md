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
# Warmup Iteration   1: 3.120 ops/ms
# Warmup Iteration   2: 6.564 ops/ms
# Warmup Iteration   3: 7.491 ops/ms
Iteration   1: 7.678 ops/ms
Iteration   2: 8.212 ops/ms
Iteration   3: 8.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.183 ±(99.9%) 8.964 ops/ms [Average]
  (min, avg, max) = (7.678, 8.183, 8.659), stdev = 0.491
  CI (99.9%): [≈ 0, 17.147] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.621 ops/ms
# Warmup Iteration   2: 8.161 ops/ms
# Warmup Iteration   3: 9.048 ops/ms
Iteration   1: 9.355 ops/ms
Iteration   2: 8.652 ops/ms
Iteration   3: 8.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.988 ±(99.9%) 6.439 ops/ms [Average]
  (min, avg, max) = (8.652, 8.988, 9.355), stdev = 0.353
  CI (99.9%): [2.550, 15.427] (assumes normal distribution)


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
# Warmup Iteration   1: 5.266 ops/ms
# Warmup Iteration   2: 8.194 ops/ms
# Warmup Iteration   3: 8.269 ops/ms
Iteration   1: 8.464 ops/ms
Iteration   2: 8.683 ops/ms
Iteration   3: 8.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.545 ±(99.9%) 2.201 ops/ms [Average]
  (min, avg, max) = (8.464, 8.545, 8.683), stdev = 0.121
  CI (99.9%): [6.344, 10.745] (assumes normal distribution)


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
# Warmup Iteration   1: 4.589 ops/ms
# Warmup Iteration   2: 5.945 ops/ms
# Warmup Iteration   3: 6.510 ops/ms
Iteration   1: 6.483 ops/ms
Iteration   2: 6.615 ops/ms
Iteration   3: 6.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.537 ±(99.9%) 1.258 ops/ms [Average]
  (min, avg, max) = (6.483, 6.537, 6.615), stdev = 0.069
  CI (99.9%): [5.279, 7.795] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.633 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.912 ±(99.9%) 0.012 ms/op
Iteration   1: 3.796 ±(99.9%) 0.004 ms/op
Iteration   2: 3.880 ±(99.9%) 0.002 ms/op
Iteration   3: 3.736 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.804 ±(99.9%) 1.327 ms/op [Average]
  (min, avg, max) = (3.736, 3.804, 3.880), stdev = 0.073
  CI (99.9%): [2.477, 5.131] (assumes normal distribution)


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
# Warmup Iteration   1: 5.041 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.708 ±(99.9%) 0.003 ms/op
Iteration   1: 3.551 ±(99.9%) 0.003 ms/op
Iteration   2: 3.619 ±(99.9%) 0.003 ms/op
Iteration   3: 3.565 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.578 ±(99.9%) 0.662 ms/op [Average]
  (min, avg, max) = (3.551, 3.578, 3.619), stdev = 0.036
  CI (99.9%): [2.916, 4.241] (assumes normal distribution)


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
# Warmup Iteration   1: 5.501 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.006 ms/op
Iteration   1: 3.897 ±(99.9%) 0.003 ms/op
Iteration   2: 3.781 ±(99.9%) 0.004 ms/op
Iteration   3: 3.746 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.808 ±(99.9%) 1.447 ms/op [Average]
  (min, avg, max) = (3.746, 3.808, 3.897), stdev = 0.079
  CI (99.9%): [2.361, 5.255] (assumes normal distribution)


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
# Warmup Iteration   1: 7.040 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.086 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.867 ±(99.9%) 0.020 ms/op
Iteration   1: 4.771 ±(99.9%) 0.013 ms/op
Iteration   2: 4.857 ±(99.9%) 0.016 ms/op
Iteration   3: 4.723 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.783 ±(99.9%) 1.238 ms/op [Average]
  (min, avg, max) = (4.723, 4.783, 4.857), stdev = 0.068
  CI (99.9%): [3.545, 6.022] (assumes normal distribution)


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
# Warmup Iteration   1: 5.579 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.011 ms/op
Iteration   1: 3.850 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   7.045 ms/op
                 createUser·p0.999:  10.748 ms/op
                 createUser·p0.9999: 16.762 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   2: 3.704 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  10.233 ms/op
                 createUser·p0.9999: 15.282 ms/op
                 createUser·p1.00:   15.991 ms/op

Iteration   3: 3.797 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.063 ms/op
                 createUser·p0.99:   6.382 ms/op
                 createUser·p0.999:  14.983 ms/op
                 createUser·p0.9999: 25.821 ms/op
                 createUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 254084
  mean =      3.783 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8086 
    [ 2.500,  5.000) = 232046 
    [ 5.000,  7.500) = 12474 
    [ 7.500, 10.000) = 1124 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     10.878 ms/op
     p(99.9900) =     25.218 ms/op
     p(99.9990) =     25.992 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 4.975 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.639 ±(99.9%) 0.009 ms/op
Iteration   1: 3.648 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   6.392 ms/op
                 existUser·p0.999:  10.583 ms/op
                 existUser·p0.9999: 14.355 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   2: 3.538 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   3.457 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   6.472 ms/op
                 existUser·p0.999:  10.732 ms/op
                 existUser·p0.9999: 20.151 ms/op
                 existUser·p1.00:   20.316 ms/op

Iteration   3: 3.535 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.220 ms/op
                 existUser·p0.999:  9.782 ms/op
                 existUser·p0.9999: 20.180 ms/op
                 existUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268503
  mean =      3.573 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13607 
    [ 2.500,  5.000) = 244812 
    [ 5.000,  7.500) = 8844 
    [ 7.500, 10.000) = 935 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      3.494 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     10.330 ms/op
     p(99.9900) =     19.938 ms/op
     p(99.9990) =     21.713 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 5.243 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.011 ms/op
Iteration   1: 3.827 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.992 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.226 ms/op
                 getUser·p0.99:   7.758 ms/op
                 getUser·p0.999:  12.606 ms/op
                 getUser·p0.9999: 16.092 ms/op
                 getUser·p1.00:   16.417 ms/op

Iteration   2: 3.876 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.768 ms/op
                 getUser·p0.95:   5.341 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  12.141 ms/op
                 getUser·p0.9999: 19.292 ms/op
                 getUser·p1.00:   19.595 ms/op

Iteration   3: 3.740 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.856 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.563 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.934 ms/op
                 getUser·p0.999:  10.551 ms/op
                 getUser·p0.9999: 23.429 ms/op
                 getUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251753
  mean =      3.813 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9458 
    [ 2.500,  5.000) = 226262 
    [ 5.000,  7.500) = 13707 
    [ 7.500, 10.000) = 1688 
    [10.000, 12.500) = 409 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.210 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     12.018 ms/op
     p(99.9900) =     23.057 ms/op
     p(99.9990) =     23.495 ms/op
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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.866 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.461 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.053 ±(99.9%) 0.019 ms/op
Iteration   1: 5.014 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   4.665 ms/op
                 listUser·p0.90:   6.775 ms/op
                 listUser·p0.95:   7.660 ms/op
                 listUser·p0.99:   10.093 ms/op
                 listUser·p0.999:  16.464 ms/op
                 listUser·p0.9999: 24.342 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   2: 5.134 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   6.676 ms/op
                 listUser·p0.95:   7.660 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  20.961 ms/op
                 listUser·p0.9999: 26.506 ms/op
                 listUser·p1.00:   27.525 ms/op

Iteration   3: 5.103 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.668 ms/op
                 listUser·p0.95:   7.668 ms/op
                 listUser·p0.99:   10.764 ms/op
                 listUser·p0.999:  31.544 ms/op
                 listUser·p0.9999: 35.880 ms/op
                 listUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 188875
  mean =      5.083 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 356 
    [ 2.500,  5.000) = 117810 
    [ 5.000,  7.500) = 60082 
    [ 7.500, 10.000) = 8385 
    [10.000, 12.500) = 1454 
    [12.500, 15.000) = 330 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.709 ms/op
     p(95.0000) =      7.660 ms/op
     p(99.0000) =     10.359 ms/op
     p(99.9000) =     22.057 ms/op
     p(99.9900) =     34.406 ms/op
     p(99.9990) =     36.438 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.183 ± 8.964  ops/ms
ClientGrpc.existUser                       thrpt       3   8.988 ± 6.439  ops/ms
ClientGrpc.getUser                         thrpt       3   8.545 ± 2.201  ops/ms
ClientGrpc.listUser                        thrpt       3   6.537 ± 1.258  ops/ms
ClientGrpc.createUser                       avgt       3   3.804 ± 1.327   ms/op
ClientGrpc.existUser                        avgt       3   3.578 ± 0.662   ms/op
ClientGrpc.getUser                          avgt       3   3.808 ± 1.447   ms/op
ClientGrpc.listUser                         avgt       3   4.783 ± 1.238   ms/op
ClientGrpc.createUser                     sample  254084   3.783 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.800           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.063           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.652           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.878           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.218           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.411           ms/op
ClientGrpc.existUser                      sample  268503   3.573 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.860           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.792           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.373           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.330           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.938           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.758           ms/op
ClientGrpc.getUser                        sample  251753   3.813 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.843           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.210           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.348           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.018           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.057           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.495           ms/op
ClientGrpc.listUser                       sample  188875   5.083 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.008           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.735           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.709           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.660           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.359           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.057           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.406           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.438           ms/op
