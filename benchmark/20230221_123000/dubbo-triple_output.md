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
# Warmup Iteration   1: 2.492 ops/ms
# Warmup Iteration   2: 6.628 ops/ms
# Warmup Iteration   3: 9.342 ops/ms
Iteration   1: 9.862 ops/ms
Iteration   2: 10.107 ops/ms
Iteration   3: 10.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.017 ±(99.9%) 2.461 ops/ms [Average]
  (min, avg, max) = (9.862, 10.017, 10.107), stdev = 0.135
  CI (99.9%): [7.556, 12.478] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.452 ops/ms
# Warmup Iteration   2: 9.574 ops/ms
# Warmup Iteration   3: 10.008 ops/ms
Iteration   1: 10.807 ops/ms
Iteration   2: 10.445 ops/ms
Iteration   3: 10.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.688 ±(99.9%) 3.846 ops/ms [Average]
  (min, avg, max) = (10.445, 10.688, 10.812), stdev = 0.211
  CI (99.9%): [6.842, 14.534] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.671 ops/ms
# Warmup Iteration   2: 9.048 ops/ms
# Warmup Iteration   3: 9.273 ops/ms
Iteration   1: 9.479 ops/ms
Iteration   2: 9.726 ops/ms
Iteration   3: 9.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.685 ±(99.9%) 3.455 ops/ms [Average]
  (min, avg, max) = (9.479, 9.685, 9.852), stdev = 0.189
  CI (99.9%): [6.230, 13.141] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.493 ops/ms
# Warmup Iteration   2: 7.845 ops/ms
# Warmup Iteration   3: 8.386 ops/ms
Iteration   1: 8.731 ops/ms
Iteration   2: 8.761 ops/ms
Iteration   3: 8.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.774 ±(99.9%) 0.930 ops/ms [Average]
  (min, avg, max) = (8.731, 8.774, 8.831), stdev = 0.051
  CI (99.9%): [7.844, 9.705] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.442 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.442 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.005 ms/op
Iteration   1: 3.114 ±(99.9%) 0.007 ms/op
Iteration   2: 3.264 ±(99.9%) 0.006 ms/op
Iteration   3: 3.057 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.145 ±(99.9%) 1.953 ms/op [Average]
  (min, avg, max) = (3.057, 3.145, 3.264), stdev = 0.107
  CI (99.9%): [1.193, 5.098] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.322 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.074 ±(99.9%) 0.001 ms/op
Iteration   2: 3.013 ±(99.9%) 0.007 ms/op
Iteration   3: 2.979 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.022 ±(99.9%) 0.876 ms/op [Average]
  (min, avg, max) = (2.979, 3.022, 3.074), stdev = 0.048
  CI (99.9%): [2.146, 3.898] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.235 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.007 ms/op
Iteration   1: 3.204 ±(99.9%) 0.003 ms/op
Iteration   2: 3.213 ±(99.9%) 0.006 ms/op
Iteration   3: 3.101 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.173 ±(99.9%) 1.137 ms/op [Average]
  (min, avg, max) = (3.101, 3.173, 3.213), stdev = 0.062
  CI (99.9%): [2.036, 4.310] (assumes normal distribution)


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
# Warmup Iteration   1: 8.661 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.007 ms/op
Iteration   1: 3.833 ±(99.9%) 0.004 ms/op
Iteration   2: 3.682 ±(99.9%) 0.010 ms/op
Iteration   3: 3.716 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.744 ±(99.9%) 1.443 ms/op [Average]
  (min, avg, max) = (3.682, 3.744, 3.833), stdev = 0.079
  CI (99.9%): [2.301, 5.186] (assumes normal distribution)


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
# Warmup Iteration   1: 8.433 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.728 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.008 ms/op
Iteration   1: 3.211 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.417 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  12.747 ms/op
                 createUser·p0.9999: 22.581 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   2: 3.136 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.426 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  20.506 ms/op
                 createUser·p0.9999: 23.193 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   3: 3.183 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  9.696 ms/op
                 createUser·p0.9999: 24.830 ms/op
                 createUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302071
  mean =      3.176 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21933 
    [ 2.500,  5.000) = 274776 
    [ 5.000,  7.500) = 4749 
    [ 7.500, 10.000) = 233 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 164 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.426 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     16.563 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     25.756 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 7.768 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.405 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
Iteration   1: 3.112 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   5.398 ms/op
                 existUser·p0.999:  10.799 ms/op
                 existUser·p0.9999: 19.684 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   2: 3.036 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.298 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  14.276 ms/op
                 existUser·p0.9999: 21.037 ms/op
                 existUser·p1.00:   21.529 ms/op

Iteration   3: 3.074 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.206 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  14.811 ms/op
                 existUser·p0.9999: 22.643 ms/op
                 existUser·p1.00:   22.839 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312234
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21554 
    [ 2.500,  5.000) = 285263 
    [ 5.000,  7.500) = 4416 
    [ 7.500, 10.000) = 449 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 154 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     21.656 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


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
# Warmup Iteration   1: 7.987 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.009 ms/op
Iteration   1: 3.274 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  17.870 ms/op
                 getUser·p0.9999: 25.509 ms/op
                 getUser·p1.00:   26.149 ms/op

Iteration   2: 3.187 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   5.455 ms/op
                 getUser·p0.999:  9.784 ms/op
                 getUser·p0.9999: 23.491 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   3: 3.263 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  17.531 ms/op
                 getUser·p0.9999: 21.627 ms/op
                 getUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 296068
  mean =      3.241 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15647 
    [ 2.500,  5.000) = 270991 
    [ 5.000,  7.500) = 8435 
    [ 7.500, 10.000) = 571 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 60 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.351 ms/op
     p(99.9000) =     17.723 ms/op
     p(99.9900) =     23.861 ms/op
     p(99.9990) =     25.888 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 9.262 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.172 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.012 ms/op
Iteration   1: 3.843 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.999 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   7.550 ms/op
                 listUser·p0.999:  15.856 ms/op
                 listUser·p0.9999: 22.339 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   2: 3.741 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.181 ms/op
                 listUser·p0.999:  16.269 ms/op
                 listUser·p0.9999: 19.204 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   3: 3.690 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.886 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  12.091 ms/op
                 listUser·p0.9999: 17.596 ms/op
                 listUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255192
  mean =      3.757 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 245470 
    [ 5.000,  7.500) = 7677 
    [ 7.500, 10.000) = 1265 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     15.696 ms/op
     p(99.9900) =     21.249 ms/op
     p(99.9990) =     22.687 ms/op
     p(99.9999) =     22.839 ms/op
    p(100.0000) =     22.839 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.017 ± 2.461  ops/ms
ClientPb.existUser                       thrpt       3  10.688 ± 3.846  ops/ms
ClientPb.getUser                         thrpt       3   9.685 ± 3.455  ops/ms
ClientPb.listUser                        thrpt       3   8.774 ± 0.930  ops/ms
ClientPb.createUser                       avgt       3   3.145 ± 1.953   ms/op
ClientPb.existUser                        avgt       3   3.022 ± 0.876   ms/op
ClientPb.getUser                          avgt       3   3.173 ± 1.137   ms/op
ClientPb.listUser                         avgt       3   3.744 ± 1.443   ms/op
ClientPb.createUser                     sample  302071   3.176 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.426           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.138           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.506           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.366           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.563           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.527           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.821           ms/op
ClientPb.existUser                      sample  312234   3.073 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.206           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.382           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.254           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.656           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.839           ms/op
ClientPb.getUser                        sample  296068   3.241 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.934           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.662           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.351           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.723           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.861           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.149           ms/op
ClientPb.listUser                       sample  255192   3.757 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.473           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.633           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.104           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.086           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.696           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.249           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.839           ms/op
