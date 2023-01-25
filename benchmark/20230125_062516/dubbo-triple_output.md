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
# Warmup Iteration   1: 2.714 ops/ms
# Warmup Iteration   2: 5.733 ops/ms
# Warmup Iteration   3: 9.164 ops/ms
Iteration   1: 10.092 ops/ms
Iteration   2: 10.070 ops/ms
Iteration   3: 9.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.956 ±(99.9%) 3.942 ops/ms [Average]
  (min, avg, max) = (9.707, 9.956, 10.092), stdev = 0.216
  CI (99.9%): [6.014, 13.898] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.928 ops/ms
# Warmup Iteration   2: 9.563 ops/ms
# Warmup Iteration   3: 10.253 ops/ms
Iteration   1: 10.435 ops/ms
Iteration   2: 10.494 ops/ms
Iteration   3: 10.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.362 ±(99.9%) 3.267 ops/ms [Average]
  (min, avg, max) = (10.158, 10.362, 10.494), stdev = 0.179
  CI (99.9%): [7.096, 13.629] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.890 ops/ms
# Warmup Iteration   2: 9.209 ops/ms
# Warmup Iteration   3: 9.945 ops/ms
Iteration   1: 9.952 ops/ms
Iteration   2: 9.783 ops/ms
Iteration   3: 9.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.872 ±(99.9%) 1.553 ops/ms [Average]
  (min, avg, max) = (9.783, 9.872, 9.952), stdev = 0.085
  CI (99.9%): [8.320, 11.425] (assumes normal distribution)


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
# Warmup Iteration   1: 3.433 ops/ms
# Warmup Iteration   2: 7.751 ops/ms
# Warmup Iteration   3: 8.227 ops/ms
Iteration   1: 8.702 ops/ms
Iteration   2: 8.785 ops/ms
Iteration   3: 8.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.648 ±(99.9%) 3.110 ops/ms [Average]
  (min, avg, max) = (8.457, 8.648, 8.785), stdev = 0.170
  CI (99.9%): [5.537, 11.758] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 7.913 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.567 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.452 ±(99.9%) 0.007 ms/op
Iteration   1: 3.291 ±(99.9%) 0.006 ms/op
Iteration   2: 3.320 ±(99.9%) 0.006 ms/op
Iteration   3: 3.188 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.266 ±(99.9%) 1.263 ms/op [Average]
  (min, avg, max) = (3.188, 3.266, 3.320), stdev = 0.069
  CI (99.9%): [2.003, 4.529] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.517 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.469 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.002 ms/op
Iteration   1: 3.216 ±(99.9%) 0.003 ms/op
Iteration   2: 3.194 ±(99.9%) 0.004 ms/op
Iteration   3: 3.076 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.162 ±(99.9%) 1.374 ms/op [Average]
  (min, avg, max) = (3.076, 3.162, 3.216), stdev = 0.075
  CI (99.9%): [1.788, 4.535] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 7.901 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.325 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.004 ms/op
Iteration   1: 3.084 ±(99.9%) 0.002 ms/op
Iteration   2: 3.275 ±(99.9%) 0.006 ms/op
Iteration   3: 3.250 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.203 ±(99.9%) 1.897 ms/op [Average]
  (min, avg, max) = (3.084, 3.203, 3.275), stdev = 0.104
  CI (99.9%): [1.306, 5.099] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.498 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.852 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.707 ±(99.9%) 0.007 ms/op
Iteration   1: 3.727 ±(99.9%) 0.007 ms/op
Iteration   2: 3.819 ±(99.9%) 0.008 ms/op
Iteration   3: 3.707 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.751 ±(99.9%) 1.088 ms/op [Average]
  (min, avg, max) = (3.707, 3.751, 3.819), stdev = 0.060
  CI (99.9%): [2.663, 4.839] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.587 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
Iteration   1: 3.125 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  8.913 ms/op
                 createUser·p0.9999: 24.601 ms/op
                 createUser·p1.00:   25.494 ms/op

Iteration   2: 3.249 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  14.729 ms/op
                 createUser·p0.9999: 21.978 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   3: 3.285 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  14.722 ms/op
                 createUser·p0.9999: 28.756 ms/op
                 createUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298210
  mean =      3.218 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17619 
    [ 2.500,  5.000) = 275747 
    [ 5.000,  7.500) = 3963 
    [ 7.500, 10.000) = 368 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     28.219 ms/op
     p(99.9990) =     29.295 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.466 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.420 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.008 ms/op
Iteration   1: 3.002 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.929 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.170 ms/op
                 existUser·p0.95:   3.330 ms/op
                 existUser·p0.99:   5.095 ms/op
                 existUser·p0.999:  13.107 ms/op
                 existUser·p0.9999: 19.366 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   2: 3.259 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   5.005 ms/op
                 existUser·p0.999:  10.084 ms/op
                 existUser·p0.9999: 26.706 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.327 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.923 ms/op
                 existUser·p0.999:  9.196 ms/op
                 existUser·p0.9999: 20.471 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 307449
  mean =      3.120 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13458 
    [ 2.500,  5.000) = 290883 
    [ 5.000,  7.500) = 2476 
    [ 7.500, 10.000) = 250 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.929 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     25.248 ms/op
     p(99.9990) =     27.293 ms/op
     p(99.9999) =     27.558 ms/op
    p(100.0000) =     27.558 ms/op


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
# Warmup Iteration   1: 7.510 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.464 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.271 ±(99.9%) 0.009 ms/op
Iteration   1: 3.359 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.537 ms/op
                 getUser·p0.999:  18.139 ms/op
                 getUser·p0.9999: 20.742 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   2: 3.086 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.330 ms/op
                 getUser·p0.95:   3.490 ms/op
                 getUser·p0.99:   5.194 ms/op
                 getUser·p0.999:  10.027 ms/op
                 getUser·p0.9999: 23.921 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   3: 3.161 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.040 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.160 ms/op
                 getUser·p0.999:  11.643 ms/op
                 getUser·p0.9999: 24.527 ms/op
                 getUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300039
  mean =      3.198 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11555 
    [ 2.500,  5.000) = 281128 
    [ 5.000,  7.500) = 6553 
    [ 7.500, 10.000) = 346 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     11.795 ms/op
     p(99.9900) =     23.921 ms/op
     p(99.9990) =     25.723 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 8.685 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.012 ms/op
Iteration   1: 3.775 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.602 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  15.635 ms/op
                 listUser·p0.9999: 18.630 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   2: 3.713 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  13.024 ms/op
                 listUser·p0.9999: 15.272 ms/op
                 listUser·p1.00:   16.597 ms/op

Iteration   3: 3.630 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   3.826 ms/op
                 listUser·p0.95:   4.080 ms/op
                 listUser·p0.99:   6.219 ms/op
                 listUser·p0.999:  12.780 ms/op
                 listUser·p0.9999: 14.421 ms/op
                 listUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258854
  mean =      3.705 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 71 
    [ 2.500,  3.750) = 199196 
    [ 3.750,  5.000) = 53434 
    [ 5.000,  6.250) = 2640 
    [ 6.250,  7.500) = 1818 
    [ 7.500,  8.750) = 777 
    [ 8.750, 10.000) = 224 
    [10.000, 11.250) = 132 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 243 
    [13.750, 15.000) = 96 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.602 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.836 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     18.256 ms/op
     p(99.9990) =     19.059 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.956 ± 3.942  ops/ms
ClientPb.existUser                       thrpt       3  10.362 ± 3.267  ops/ms
ClientPb.getUser                         thrpt       3   9.872 ± 1.553  ops/ms
ClientPb.listUser                        thrpt       3   8.648 ± 3.110  ops/ms
ClientPb.createUser                       avgt       3   3.266 ± 1.263   ms/op
ClientPb.existUser                        avgt       3   3.162 ± 1.374   ms/op
ClientPb.getUser                          avgt       3   3.203 ± 1.897   ms/op
ClientPb.listUser                         avgt       3   3.751 ± 1.088   ms/op
ClientPb.createUser                     sample  298210   3.218 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.913           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.325           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.729           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.219           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.360           ms/op
ClientPb.existUser                      sample  307449   3.120 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.929           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.006           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.005           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.960           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.248           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.558           ms/op
ClientPb.getUser                        sample  300039   3.198 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.040           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.592           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.990           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.005           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.795           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.921           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.394           ms/op
ClientPb.listUser                       sample  258854   3.705 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.602           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.030           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.836           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.238           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.256           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.300           ms/op
