# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.546 ops/ms
# Warmup Iteration   2: 5.629 ops/ms
# Warmup Iteration   3: 9.241 ops/ms
Iteration   1: 9.452 ops/ms
Iteration   2: 9.758 ops/ms
Iteration   3: 9.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.669 ±(99.9%) 3.435 ops/ms [Average]
  (min, avg, max) = (9.452, 9.669, 9.796), stdev = 0.188
  CI (99.9%): [6.234, 13.104] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.279 ops/ms
# Warmup Iteration   2: 8.535 ops/ms
# Warmup Iteration   3: 9.855 ops/ms
Iteration   1: 10.060 ops/ms
Iteration   2: 10.093 ops/ms
Iteration   3: 10.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.095 ±(99.9%) 0.653 ops/ms [Average]
  (min, avg, max) = (10.060, 10.095, 10.131), stdev = 0.036
  CI (99.9%): [9.442, 10.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.543 ops/ms
# Warmup Iteration   2: 8.845 ops/ms
# Warmup Iteration   3: 9.585 ops/ms
Iteration   1: 9.853 ops/ms
Iteration   2: 9.672 ops/ms
Iteration   3: 10.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.856 ±(99.9%) 3.395 ops/ms [Average]
  (min, avg, max) = (9.672, 9.856, 10.044), stdev = 0.186
  CI (99.9%): [6.461, 13.251] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 3.218 ops/ms
# Warmup Iteration   2: 7.725 ops/ms
# Warmup Iteration   3: 8.191 ops/ms
Iteration   1: 8.213 ops/ms
Iteration   2: 8.334 ops/ms
Iteration   3: 8.299 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.282 ±(99.9%) 1.141 ops/ms [Average]
  (min, avg, max) = (8.213, 8.282, 8.334), stdev = 0.063
  CI (99.9%): [7.141, 9.423] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.412 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.399 ±(99.9%) 0.005 ms/op
Iteration   1: 3.253 ±(99.9%) 0.005 ms/op
Iteration   2: 3.249 ±(99.9%) 0.006 ms/op
Iteration   3: 3.324 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.275 ±(99.9%) 0.762 ms/op [Average]
  (min, avg, max) = (3.249, 3.275, 3.324), stdev = 0.042
  CI (99.9%): [2.513, 4.037] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.575 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.467 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.003 ms/op
Iteration   1: 3.175 ±(99.9%) 0.003 ms/op
Iteration   2: 3.159 ±(99.9%) 0.004 ms/op
Iteration   3: 3.204 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.179 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (3.159, 3.179, 3.204), stdev = 0.023
  CI (99.9%): [2.764, 3.595] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.189 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.522 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.002 ms/op
Iteration   1: 3.315 ±(99.9%) 0.004 ms/op
Iteration   2: 3.206 ±(99.9%) 0.003 ms/op
Iteration   3: 3.231 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.251 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (3.206, 3.251, 3.315), stdev = 0.057
  CI (99.9%): [2.212, 4.289] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.479 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.952 ±(99.9%) 0.007 ms/op
Iteration   1: 3.804 ±(99.9%) 0.006 ms/op
Iteration   2: 3.822 ±(99.9%) 0.005 ms/op
Iteration   3: 3.848 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.824 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (3.804, 3.824, 3.848), stdev = 0.022
  CI (99.9%): [3.421, 4.228] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.242 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.648 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.415 ±(99.9%) 0.012 ms/op
Iteration   1: 3.307 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  17.797 ms/op
                 createUser·p0.9999: 24.390 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   2: 3.270 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  19.143 ms/op
                 createUser·p0.9999: 21.870 ms/op
                 createUser·p1.00:   22.479 ms/op

Iteration   3: 3.287 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  17.236 ms/op
                 createUser·p0.9999: 25.348 ms/op
                 createUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291999
  mean =      3.288 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13467 
    [ 2.500,  5.000) = 272012 
    [ 5.000,  7.500) = 5358 
    [ 7.500, 10.000) = 573 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     24.687 ms/op
     p(99.9990) =     25.938 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.531 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.182 ±(99.9%) 0.009 ms/op
Iteration   1: 3.232 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   6.554 ms/op
                 existUser·p0.999:  18.874 ms/op
                 existUser·p0.9999: 24.157 ms/op
                 existUser·p1.00:   24.871 ms/op

Iteration   2: 3.130 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   6.223 ms/op
                 existUser·p0.999:  13.658 ms/op
                 existUser·p0.9999: 24.274 ms/op
                 existUser·p1.00:   25.199 ms/op

Iteration   3: 3.179 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  17.776 ms/op
                 existUser·p0.9999: 29.358 ms/op
                 existUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301656
  mean =      3.180 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19345 
    [ 2.500,  5.000) = 275247 
    [ 5.000,  7.500) = 6002 
    [ 7.500, 10.000) = 512 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     17.411 ms/op
     p(99.9900) =     27.716 ms/op
     p(99.9990) =     29.557 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.523 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.012 ms/op
Iteration   1: 3.296 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  17.072 ms/op
                 getUser·p0.9999: 20.054 ms/op
                 getUser·p1.00:   20.906 ms/op

Iteration   2: 3.259 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   5.998 ms/op
                 getUser·p0.999:  16.085 ms/op
                 getUser·p0.9999: 22.217 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   3: 3.327 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   6.763 ms/op
                 getUser·p0.999:  15.594 ms/op
                 getUser·p0.9999: 22.131 ms/op
                 getUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291218
  mean =      3.294 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7808 
    [ 2.500,  5.000) = 274920 
    [ 5.000,  7.500) = 7417 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.621 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      6.585 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     22.616 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.855 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.236 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.932 ±(99.9%) 0.012 ms/op
Iteration   1: 3.855 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.161 ms/op
                 listUser·p0.999:  16.943 ms/op
                 listUser·p0.9999: 19.618 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   2: 3.915 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.032 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.516 ms/op
                 listUser·p0.999:  14.189 ms/op
                 listUser·p0.9999: 26.471 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   3: 3.805 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  11.993 ms/op
                 listUser·p0.9999: 17.452 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248662
  mean =      3.858 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 129 
    [ 2.500,  5.000) = 239889 
    [ 5.000,  7.500) = 6275 
    [ 7.500, 10.000) = 1597 
    [10.000, 12.500) = 295 
    [12.500, 15.000) = 275 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     14.205 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     27.493 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.669 ± 3.435  ops/ms
ClientPb.existUser                       thrpt       3  10.095 ± 0.653  ops/ms
ClientPb.getUser                         thrpt       3   9.856 ± 3.395  ops/ms
ClientPb.listUser                        thrpt       3   8.282 ± 1.141  ops/ms
ClientPb.createUser                       avgt       3   3.275 ± 0.762   ms/op
ClientPb.existUser                        avgt       3   3.179 ± 0.416   ms/op
ClientPb.getUser                          avgt       3   3.251 ± 1.039   ms/op
ClientPb.listUser                         avgt       3   3.824 ± 0.404   ms/op
ClientPb.createUser                     sample  291999   3.288 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.886           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.218           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.727           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.687           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.673           ms/op
ClientPb.existUser                      sample  301656   3.180 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.026           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.490           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.103           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.411           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.716           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.638           ms/op
ClientPb.getUser                        sample  291218   3.294 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.822           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.621           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.585           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.696           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.118           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.872           ms/op
ClientPb.listUser                       sample  248662   3.858 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.413           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.194           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.422           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.205           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.133           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.591           ms/op
