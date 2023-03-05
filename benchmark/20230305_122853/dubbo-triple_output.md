# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.781 ops/ms
# Warmup Iteration   2: 6.410 ops/ms
# Warmup Iteration   3: 9.402 ops/ms
Iteration   1: 9.612 ops/ms
Iteration   2: 9.752 ops/ms
Iteration   3: 9.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.757 ±(99.9%) 2.690 ops/ms [Average]
  (min, avg, max) = (9.612, 9.757, 9.907), stdev = 0.147
  CI (99.9%): [7.067, 12.447] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.712 ops/ms
# Warmup Iteration   2: 9.496 ops/ms
# Warmup Iteration   3: 10.248 ops/ms
Iteration   1: 9.890 ops/ms
Iteration   2: 10.682 ops/ms
Iteration   3: 9.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.128 ±(99.9%) 8.778 ops/ms [Average]
  (min, avg, max) = (9.812, 10.128, 10.682), stdev = 0.481
  CI (99.9%): [1.350, 18.906] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.718 ops/ms
# Warmup Iteration   2: 9.543 ops/ms
# Warmup Iteration   3: 9.901 ops/ms
Iteration   1: 9.593 ops/ms
Iteration   2: 10.191 ops/ms
Iteration   3: 9.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.747 ±(99.9%) 7.134 ops/ms [Average]
  (min, avg, max) = (9.456, 9.747, 10.191), stdev = 0.391
  CI (99.9%): [2.613, 16.880] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.426 ops/ms
# Warmup Iteration   2: 7.814 ops/ms
# Warmup Iteration   3: 8.350 ops/ms
Iteration   1: 8.785 ops/ms
Iteration   2: 8.569 ops/ms
Iteration   3: 8.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.712 ±(99.9%) 2.269 ops/ms [Average]
  (min, avg, max) = (8.569, 8.712, 8.785), stdev = 0.124
  CI (99.9%): [6.444, 10.981] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.989 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.399 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.007 ms/op
Iteration   1: 3.264 ±(99.9%) 0.009 ms/op
Iteration   2: 3.175 ±(99.9%) 0.009 ms/op
Iteration   3: 3.189 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.209 ±(99.9%) 0.880 ms/op [Average]
  (min, avg, max) = (3.175, 3.209, 3.264), stdev = 0.048
  CI (99.9%): [2.330, 4.089] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.251 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.340 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.241 ±(99.9%) 0.007 ms/op
Iteration   1: 3.094 ±(99.9%) 0.003 ms/op
Iteration   2: 3.053 ±(99.9%) 0.008 ms/op
Iteration   3: 2.971 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.039 ±(99.9%) 1.148 ms/op [Average]
  (min, avg, max) = (2.971, 3.039, 3.094), stdev = 0.063
  CI (99.9%): [1.891, 4.187] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.955 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.447 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.009 ms/op
Iteration   1: 3.100 ±(99.9%) 0.006 ms/op
Iteration   2: 3.084 ±(99.9%) 0.007 ms/op
Iteration   3: 3.248 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.144 ±(99.9%) 1.651 ms/op [Average]
  (min, avg, max) = (3.084, 3.144, 3.248), stdev = 0.091
  CI (99.9%): [1.493, 4.795] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.741 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.970 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.004 ms/op
Iteration   1: 3.771 ±(99.9%) 0.005 ms/op
Iteration   2: 3.628 ±(99.9%) 0.010 ms/op
Iteration   3: 3.717 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.705 ±(99.9%) 1.317 ms/op [Average]
  (min, avg, max) = (3.628, 3.705, 3.771), stdev = 0.072
  CI (99.9%): [2.389, 5.022] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.753 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.770 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.233 ±(99.9%) 0.008 ms/op
Iteration   1: 3.184 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  18.612 ms/op
                 createUser·p0.9999: 26.409 ms/op
                 createUser·p1.00:   27.918 ms/op

Iteration   2: 3.294 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  18.473 ms/op
                 createUser·p0.9999: 22.413 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   3: 3.316 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  16.237 ms/op
                 createUser·p0.9999: 21.070 ms/op
                 createUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294073
  mean =      3.264 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17569 
    [ 2.500,  5.000) = 269963 
    [ 5.000,  7.500) = 5470 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 152 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 151 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     18.186 ms/op
     p(99.9900) =     26.076 ms/op
     p(99.9990) =     27.658 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.159 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.008 ms/op
Iteration   1: 3.069 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.855 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  7.863 ms/op
                 existUser·p0.9999: 26.870 ms/op
                 existUser·p1.00:   27.689 ms/op

Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  11.076 ms/op
                 existUser·p0.9999: 23.200 ms/op
                 existUser·p1.00:   23.691 ms/op

Iteration   3: 3.132 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  16.807 ms/op
                 existUser·p0.9999: 34.642 ms/op
                 existUser·p1.00:   35.389 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307768
  mean =      3.115 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21539 
    [ 2.500,  5.000) = 280162 
    [ 5.000,  7.500) = 5367 
    [ 7.500, 10.000) = 283 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     16.335 ms/op
     p(99.9900) =     32.277 ms/op
     p(99.9990) =     35.188 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.617 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.490 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.008 ms/op
Iteration   1: 3.181 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.636 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  16.269 ms/op
                 getUser·p0.9999: 25.000 ms/op
                 getUser·p1.00:   26.640 ms/op

Iteration   2: 3.231 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.494 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   5.612 ms/op
                 getUser·p0.999:  13.317 ms/op
                 getUser·p0.9999: 23.465 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   3: 3.158 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.456 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.370 ms/op
                 getUser·p0.999:  11.348 ms/op
                 getUser·p0.9999: 22.924 ms/op
                 getUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300981
  mean =      3.190 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14117 
    [ 2.500,  5.000) = 280318 
    [ 5.000,  7.500) = 5570 
    [ 7.500, 10.000) = 530 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     23.724 ms/op
     p(99.9990) =     26.530 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.170 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.012 ms/op
Iteration   1: 3.738 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.825 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.010 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  16.052 ms/op
                 listUser·p0.9999: 22.573 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   2: 3.782 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.212 ms/op
                 listUser·p0.50:   3.637 ms/op
                 listUser·p0.90:   4.141 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 19.628 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 3.763 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 19.792 ms/op
                 listUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255148
  mean =      3.761 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 246790 
    [ 5.000,  7.500) = 6450 
    [ 7.500, 10.000) = 1160 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 238 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.825 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     14.563 ms/op
     p(99.9900) =     21.035 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.757 ± 2.690  ops/ms
ClientPb.existUser                       thrpt       3  10.128 ± 8.778  ops/ms
ClientPb.getUser                         thrpt       3   9.747 ± 7.134  ops/ms
ClientPb.listUser                        thrpt       3   8.712 ± 2.269  ops/ms
ClientPb.createUser                       avgt       3   3.209 ± 0.880   ms/op
ClientPb.existUser                        avgt       3   3.039 ± 1.148   ms/op
ClientPb.getUser                          avgt       3   3.144 ± 1.651   ms/op
ClientPb.listUser                         avgt       3   3.705 ± 1.317   ms/op
ClientPb.createUser                     sample  294073   3.264 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.911           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.186           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.076           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.918           ms/op
ClientPb.existUser                      sample  307768   3.115 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.855           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.420           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.335           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.277           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.389           ms/op
ClientPb.getUser                        sample  300981   3.190 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.494           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.535           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.964           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.073           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.724           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.640           ms/op
ClientPb.listUser                       sample  255148   3.761 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.825           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.051           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.029           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.563           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.035           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.233           ms/op
