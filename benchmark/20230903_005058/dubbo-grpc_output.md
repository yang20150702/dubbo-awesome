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
# Warmup Iteration   1: 2.958 ops/ms
# Warmup Iteration   2: 6.447 ops/ms
# Warmup Iteration   3: 7.745 ops/ms
Iteration   1: 8.199 ops/ms
Iteration   2: 8.343 ops/ms
Iteration   3: 8.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.294 ±(99.9%) 1.495 ops/ms [Average]
  (min, avg, max) = (8.199, 8.294, 8.343), stdev = 0.082
  CI (99.9%): [6.799, 9.788] (assumes normal distribution)


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
# Warmup Iteration   1: 5.238 ops/ms
# Warmup Iteration   2: 8.104 ops/ms
# Warmup Iteration   3: 8.642 ops/ms
Iteration   1: 8.620 ops/ms
Iteration   2: 8.709 ops/ms
Iteration   3: 8.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.684 ±(99.9%) 1.012 ops/ms [Average]
  (min, avg, max) = (8.620, 8.684, 8.722), stdev = 0.055
  CI (99.9%): [7.672, 9.696] (assumes normal distribution)


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
# Warmup Iteration   1: 5.177 ops/ms
# Warmup Iteration   2: 7.687 ops/ms
# Warmup Iteration   3: 8.037 ops/ms
Iteration   1: 8.341 ops/ms
Iteration   2: 8.413 ops/ms
Iteration   3: 8.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.384 ±(99.9%) 0.702 ops/ms [Average]
  (min, avg, max) = (8.341, 8.384, 8.413), stdev = 0.039
  CI (99.9%): [7.682, 9.087] (assumes normal distribution)


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
# Warmup Iteration   1: 4.641 ops/ms
# Warmup Iteration   2: 5.575 ops/ms
# Warmup Iteration   3: 6.377 ops/ms
Iteration   1: 6.464 ops/ms
Iteration   2: 6.460 ops/ms
Iteration   3: 6.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.482 ±(99.9%) 0.637 ops/ms [Average]
  (min, avg, max) = (6.460, 6.482, 6.522), stdev = 0.035
  CI (99.9%): [5.845, 7.119] (assumes normal distribution)


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
# Warmup Iteration   1: 5.674 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.010 ms/op
Iteration   1: 3.840 ±(99.9%) 0.003 ms/op
Iteration   2: 3.876 ±(99.9%) 0.003 ms/op
Iteration   3: 3.831 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.849 ±(99.9%) 0.436 ms/op [Average]
  (min, avg, max) = (3.831, 3.849, 3.876), stdev = 0.024
  CI (99.9%): [3.414, 4.285] (assumes normal distribution)


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
# Warmup Iteration   1: 5.136 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.832 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.740 ±(99.9%) 0.003 ms/op
Iteration   1: 3.683 ±(99.9%) 0.003 ms/op
Iteration   2: 3.628 ±(99.9%) 0.004 ms/op
Iteration   3: 3.603 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.638 ±(99.9%) 0.743 ms/op [Average]
  (min, avg, max) = (3.603, 3.638, 3.683), stdev = 0.041
  CI (99.9%): [2.895, 4.381] (assumes normal distribution)


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
# Warmup Iteration   1: 5.497 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.004 ms/op
Iteration   1: 3.831 ±(99.9%) 0.005 ms/op
Iteration   2: 3.860 ±(99.9%) 0.004 ms/op
Iteration   3: 3.853 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.848 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (3.831, 3.848, 3.860), stdev = 0.015
  CI (99.9%): [3.569, 4.127] (assumes normal distribution)


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
# Warmup Iteration   1: 6.013 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 5.393 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.105 ±(99.9%) 0.017 ms/op
Iteration   1: 5.146 ±(99.9%) 0.015 ms/op
Iteration   2: 4.982 ±(99.9%) 0.014 ms/op
Iteration   3: 4.912 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.013 ±(99.9%) 2.188 ms/op [Average]
  (min, avg, max) = (4.912, 5.013, 5.146), stdev = 0.120
  CI (99.9%): [2.825, 7.201] (assumes normal distribution)


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
# Warmup Iteration   1: 5.557 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.011 ms/op
Iteration   1: 3.813 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.715 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.638 ms/op
                 createUser·p0.999:  12.724 ms/op
                 createUser·p0.9999: 19.479 ms/op
                 createUser·p1.00:   21.103 ms/op

Iteration   2: 3.822 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  10.103 ms/op
                 createUser·p0.9999: 21.570 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   3: 3.847 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.731 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   7.477 ms/op
                 createUser·p0.999:  20.017 ms/op
                 createUser·p0.9999: 25.035 ms/op
                 createUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 250690
  mean =      3.827 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7763 
    [ 2.500,  5.000) = 229924 
    [ 5.000,  7.500) = 11307 
    [ 7.500, 10.000) = 1230 
    [10.000, 12.500) = 237 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     12.113 ms/op
     p(99.9900) =     24.672 ms/op
     p(99.9990) =     25.587 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


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
# Warmup Iteration   1: 5.037 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.900 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.708 ±(99.9%) 0.010 ms/op
Iteration   1: 3.725 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   5.005 ms/op
                 existUser·p0.99:   7.410 ms/op
                 existUser·p0.999:  12.288 ms/op
                 existUser·p0.9999: 28.437 ms/op
                 existUser·p1.00:   29.753 ms/op

Iteration   2: 3.539 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.974 ms/op
                 existUser·p0.999:  10.846 ms/op
                 existUser·p0.9999: 26.213 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   3: 3.583 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.672 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.230 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  10.797 ms/op
                 existUser·p0.9999: 26.479 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 265439
  mean =      3.614 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12770 
    [ 2.500,  5.000) = 243945 
    [ 5.000,  7.500) = 7147 
    [ 7.500, 10.000) = 1060 
    [10.000, 12.500) = 313 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     11.862 ms/op
     p(99.9900) =     27.525 ms/op
     p(99.9990) =     29.753 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 5.366 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.041 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.833 ±(99.9%) 0.010 ms/op
Iteration   1: 3.846 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.161 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   7.332 ms/op
                 getUser·p0.999:  10.613 ms/op
                 getUser·p0.9999: 17.859 ms/op
                 getUser·p1.00:   18.055 ms/op

Iteration   2: 3.771 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  10.820 ms/op
                 getUser·p0.9999: 17.319 ms/op
                 getUser·p1.00:   17.629 ms/op

Iteration   3: 3.831 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   5.095 ms/op
                 getUser·p0.99:   7.250 ms/op
                 getUser·p0.999:  13.381 ms/op
                 getUser·p0.9999: 18.371 ms/op
                 getUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251626
  mean =      3.816 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 84 
    [ 1.250,  2.500) = 6787 
    [ 2.500,  3.750) = 123558 
    [ 3.750,  5.000) = 108944 
    [ 5.000,  6.250) = 8440 
    [ 6.250,  7.500) = 1982 
    [ 7.500,  8.750) = 923 
    [ 8.750, 10.000) = 356 
    [10.000, 11.250) = 212 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 80 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     12.567 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     18.657 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 7.754 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.295 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.071 ±(99.9%) 0.019 ms/op
Iteration   1: 4.999 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.407 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.693 ms/op
                 listUser·p0.95:   7.627 ms/op
                 listUser·p0.99:   10.258 ms/op
                 listUser·p0.999:  16.205 ms/op
                 listUser·p0.9999: 30.219 ms/op
                 listUser·p1.00:   30.933 ms/op

Iteration   2: 4.880 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.382 ms/op
                 listUser·p0.95:   7.184 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  17.055 ms/op
                 listUser·p0.9999: 35.127 ms/op
                 listUser·p1.00:   35.521 ms/op

Iteration   3: 5.080 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   6.865 ms/op
                 listUser·p0.95:   7.774 ms/op
                 listUser·p0.99:   10.273 ms/op
                 listUser·p0.999:  29.337 ms/op
                 listUser·p0.9999: 33.277 ms/op
                 listUser·p1.00:   33.686 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 192460
  mean =      4.985 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 859 
    [ 2.500,  5.000) = 125983 
    [ 5.000,  7.500) = 55613 
    [ 7.500, 10.000) = 8084 
    [10.000, 12.500) = 1294 
    [12.500, 15.000) = 307 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 33 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.188 ms/op
     p(50.0000) =      4.669 ms/op
     p(90.0000) =      6.644 ms/op
     p(95.0000) =      7.545 ms/op
     p(99.0000) =      9.994 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     33.915 ms/op
     p(99.9990) =     35.399 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.294 ± 1.495  ops/ms
ClientGrpc.existUser                       thrpt       3   8.684 ± 1.012  ops/ms
ClientGrpc.getUser                         thrpt       3   8.384 ± 0.702  ops/ms
ClientGrpc.listUser                        thrpt       3   6.482 ± 0.637  ops/ms
ClientGrpc.createUser                       avgt       3   3.849 ± 0.436   ms/op
ClientGrpc.existUser                        avgt       3   3.638 ± 0.743   ms/op
ClientGrpc.getUser                          avgt       3   3.848 ± 0.279   ms/op
ClientGrpc.listUser                         avgt       3   5.013 ± 2.188   ms/op
ClientGrpc.createUser                     sample  250690   3.827 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.715           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.030           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.791           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.113           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.672           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.083           ms/op
ClientGrpc.existUser                      sample  265439   3.614 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.672           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.694           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.537           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.862           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.525           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.753           ms/op
ClientGrpc.getUser                        sample  251626   3.816 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.833           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.981           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.849           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.567           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.055           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.792           ms/op
ClientGrpc.listUser                       sample  192460   4.985 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.188           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.669           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.545           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.994           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.859           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.915           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.521           ms/op
