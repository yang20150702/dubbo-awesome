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
# Warmup Iteration   1: 2.622 ops/ms
# Warmup Iteration   2: 6.346 ops/ms
# Warmup Iteration   3: 9.275 ops/ms
Iteration   1: 9.662 ops/ms
Iteration   2: 9.902 ops/ms
Iteration   3: 10.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.872 ±(99.9%) 3.589 ops/ms [Average]
  (min, avg, max) = (9.662, 9.872, 10.052), stdev = 0.197
  CI (99.9%): [6.283, 13.462] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.493 ops/ms
# Warmup Iteration   2: 8.942 ops/ms
# Warmup Iteration   3: 10.090 ops/ms
Iteration   1: 10.099 ops/ms
Iteration   2: 10.529 ops/ms
Iteration   3: 9.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.205 ±(99.9%) 5.225 ops/ms [Average]
  (min, avg, max) = (9.987, 10.205, 10.529), stdev = 0.286
  CI (99.9%): [4.980, 15.430] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.675 ops/ms
# Warmup Iteration   2: 8.830 ops/ms
# Warmup Iteration   3: 9.805 ops/ms
Iteration   1: 9.921 ops/ms
Iteration   2: 10.163 ops/ms
Iteration   3: 9.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.018 ±(99.9%) 2.336 ops/ms [Average]
  (min, avg, max) = (9.921, 10.018, 10.163), stdev = 0.128
  CI (99.9%): [7.682, 12.354] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.679 ops/ms
# Warmup Iteration   2: 7.968 ops/ms
# Warmup Iteration   3: 8.290 ops/ms
Iteration   1: 8.461 ops/ms
Iteration   2: 8.304 ops/ms
Iteration   3: 8.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.416 ±(99.9%) 1.777 ops/ms [Average]
  (min, avg, max) = (8.304, 8.416, 8.483), stdev = 0.097
  CI (99.9%): [6.639, 10.193] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.787 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.582 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.321 ±(99.9%) 0.006 ms/op
Iteration   1: 3.214 ±(99.9%) 0.005 ms/op
Iteration   2: 3.358 ±(99.9%) 0.006 ms/op
Iteration   3: 3.263 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.278 ±(99.9%) 1.330 ms/op [Average]
  (min, avg, max) = (3.214, 3.278, 3.358), stdev = 0.073
  CI (99.9%): [1.949, 4.608] (assumes normal distribution)


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
# Warmup Iteration   1: 7.745 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.002 ms/op
Iteration   1: 3.072 ±(99.9%) 0.004 ms/op
Iteration   2: 3.061 ±(99.9%) 0.002 ms/op
Iteration   3: 3.092 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.075 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (3.061, 3.075, 3.092), stdev = 0.016
  CI (99.9%): [2.787, 3.364] (assumes normal distribution)


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
# Warmup Iteration   1: 7.303 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.535 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.003 ms/op
Iteration   1: 3.352 ±(99.9%) 0.001 ms/op
Iteration   2: 3.286 ±(99.9%) 0.004 ms/op
Iteration   3: 3.264 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.300 ±(99.9%) 0.835 ms/op [Average]
  (min, avg, max) = (3.264, 3.300, 3.352), stdev = 0.046
  CI (99.9%): [2.465, 4.136] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.921 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.005 ms/op
Iteration   1: 3.812 ±(99.9%) 0.009 ms/op
Iteration   2: 3.769 ±(99.9%) 0.004 ms/op
Iteration   3: 3.732 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.771 ±(99.9%) 0.735 ms/op [Average]
  (min, avg, max) = (3.732, 3.771, 3.812), stdev = 0.040
  CI (99.9%): [3.036, 4.506] (assumes normal distribution)


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
# Warmup Iteration   1: 7.902 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.009 ms/op
Iteration   1: 3.201 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.356 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   5.868 ms/op
                 createUser·p0.999:  13.060 ms/op
                 createUser·p0.9999: 20.808 ms/op
                 createUser·p1.00:   21.791 ms/op

Iteration   2: 3.220 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.415 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  21.715 ms/op
                 createUser·p0.9999: 29.692 ms/op
                 createUser·p1.00:   30.409 ms/op

Iteration   3: 3.237 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.516 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  15.855 ms/op
                 createUser·p0.9999: 19.276 ms/op
                 createUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297917
  mean =      3.219 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16091 
    [ 2.500,  5.000) = 276329 
    [ 5.000,  7.500) = 4377 
    [ 7.500, 10.000) = 703 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     27.495 ms/op
     p(99.9990) =     30.183 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.213 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.009 ms/op
Iteration   1: 3.095 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.823 ms/op
                 existUser·p0.999:  11.534 ms/op
                 existUser·p0.9999: 24.412 ms/op
                 existUser·p1.00:   25.362 ms/op

Iteration   2: 3.280 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  9.552 ms/op
                 existUser·p0.9999: 25.698 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   3: 3.143 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  14.254 ms/op
                 existUser·p0.9999: 21.529 ms/op
                 existUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302821
  mean =      3.171 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22195 
    [ 2.500,  5.000) = 274932 
    [ 5.000,  7.500) = 4500 
    [ 7.500, 10.000) = 782 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.235 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     13.201 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 7.834 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.010 ms/op
Iteration   1: 3.223 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  9.958 ms/op
                 getUser·p0.9999: 20.611 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   2: 3.271 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.606 ms/op
                 getUser·p0.50:   3.187 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  10.551 ms/op
                 getUser·p0.9999: 23.626 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   3: 3.370 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   6.242 ms/op
                 getUser·p0.999:  14.564 ms/op
                 getUser·p0.9999: 21.660 ms/op
                 getUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291903
  mean =      3.287 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13693 
    [ 2.500,  5.000) = 269049 
    [ 5.000,  7.500) = 7685 
    [ 7.500, 10.000) = 1146 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     11.726 ms/op
     p(99.9900) =     22.132 ms/op
     p(99.9990) =     23.931 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 9.305 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.963 ±(99.9%) 0.013 ms/op
Iteration   1: 3.893 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.417 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.628 ms/op
                 listUser·p0.99:   7.668 ms/op
                 listUser·p0.999:  16.798 ms/op
                 listUser·p0.9999: 20.080 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   2: 3.785 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.884 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  13.664 ms/op
                 listUser·p0.9999: 15.232 ms/op
                 listUser·p1.00:   15.581 ms/op

Iteration   3: 3.769 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.130 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   7.470 ms/op
                 listUser·p0.999:  13.124 ms/op
                 listUser·p0.9999: 14.451 ms/op
                 listUser·p1.00:   14.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251468
  mean =      3.815 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 95 
    [ 2.500,  5.000) = 242755 
    [ 5.000,  7.500) = 5994 
    [ 7.500, 10.000) = 1886 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 303 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     13.861 ms/op
     p(99.9900) =     18.481 ms/op
     p(99.9990) =     20.479 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.872 ± 3.589  ops/ms
ClientPb.existUser                       thrpt       3  10.205 ± 5.225  ops/ms
ClientPb.getUser                         thrpt       3  10.018 ± 2.336  ops/ms
ClientPb.listUser                        thrpt       3   8.416 ± 1.777  ops/ms
ClientPb.createUser                       avgt       3   3.278 ± 1.330   ms/op
ClientPb.existUser                        avgt       3   3.075 ± 0.288   ms/op
ClientPb.getUser                          avgt       3   3.300 ± 0.835   ms/op
ClientPb.listUser                         avgt       3   3.771 ± 0.735   ms/op
ClientPb.createUser                     sample  297917   3.219 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.356           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.146           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.600           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.810           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.495           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.409           ms/op
ClientPb.existUser                      sample  302821   3.171 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.235           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.531           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.530           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.201           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.412           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.739           ms/op
ClientPb.getUser                        sample  291903   3.287 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.178           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.658           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.174           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.169           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.726           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.132           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.166           ms/op
ClientPb.listUser                       sample  251468   3.815 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.417           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.690           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.137           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.578           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.861           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.481           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.709           ms/op
