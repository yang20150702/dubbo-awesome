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
# Warmup Iteration   1: 1.884 ops/ms
# Warmup Iteration   2: 4.612 ops/ms
# Warmup Iteration   3: 8.290 ops/ms
Iteration   1: 8.759 ops/ms
Iteration   2: 8.774 ops/ms
Iteration   3: 8.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.838 ±(99.9%) 2.266 ops/ms [Average]
  (min, avg, max) = (8.759, 8.838, 8.981), stdev = 0.124
  CI (99.9%): [6.572, 11.103] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.874 ops/ms
# Warmup Iteration   2: 8.361 ops/ms
# Warmup Iteration   3: 9.281 ops/ms
Iteration   1: 9.362 ops/ms
Iteration   2: 9.063 ops/ms
Iteration   3: 9.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.323 ±(99.9%) 4.439 ops/ms [Average]
  (min, avg, max) = (9.063, 9.323, 9.545), stdev = 0.243
  CI (99.9%): [4.885, 13.762] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.776 ops/ms
# Warmup Iteration   2: 7.926 ops/ms
# Warmup Iteration   3: 8.611 ops/ms
Iteration   1: 8.784 ops/ms
Iteration   2: 9.075 ops/ms
Iteration   3: 9.007 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.955 ±(99.9%) 2.776 ops/ms [Average]
  (min, avg, max) = (8.784, 8.955, 9.075), stdev = 0.152
  CI (99.9%): [6.179, 11.732] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.779 ops/ms
# Warmup Iteration   2: 7.086 ops/ms
# Warmup Iteration   3: 7.422 ops/ms
Iteration   1: 7.245 ops/ms
Iteration   2: 7.484 ops/ms
Iteration   3: 7.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.485 ±(99.9%) 4.384 ops/ms [Average]
  (min, avg, max) = (7.245, 7.485, 7.726), stdev = 0.240
  CI (99.9%): [3.102, 11.869] (assumes normal distribution)


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
# Warmup Iteration   1: 10.308 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 3.800 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.006 ms/op
Iteration   1: 3.638 ±(99.9%) 0.005 ms/op
Iteration   2: 3.568 ±(99.9%) 0.003 ms/op
Iteration   3: 3.590 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.599 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (3.568, 3.599, 3.638), stdev = 0.036
  CI (99.9%): [2.945, 4.253] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.519 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.639 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.453 ±(99.9%) 0.003 ms/op
Iteration   1: 3.369 ±(99.9%) 0.007 ms/op
Iteration   2: 3.453 ±(99.9%) 0.005 ms/op
Iteration   3: 3.340 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.387 ±(99.9%) 1.068 ms/op [Average]
  (min, avg, max) = (3.340, 3.387, 3.453), stdev = 0.059
  CI (99.9%): [2.320, 4.455] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.598 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.766 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.005 ms/op
Iteration   1: 3.636 ±(99.9%) 0.003 ms/op
Iteration   2: 3.563 ±(99.9%) 0.005 ms/op
Iteration   3: 3.467 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.555 ±(99.9%) 1.542 ms/op [Average]
  (min, avg, max) = (3.467, 3.555, 3.636), stdev = 0.085
  CI (99.9%): [2.013, 5.097] (assumes normal distribution)


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
# Warmup Iteration   1: 10.620 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.501 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.338 ±(99.9%) 0.006 ms/op
Iteration   1: 4.203 ±(99.9%) 0.007 ms/op
Iteration   2: 4.182 ±(99.9%) 0.006 ms/op
Iteration   3: 4.166 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.184 ±(99.9%) 0.339 ms/op [Average]
  (min, avg, max) = (4.166, 4.184, 4.203), stdev = 0.019
  CI (99.9%): [3.845, 4.523] (assumes normal distribution)


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
# Warmup Iteration   1: 10.491 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.898 ±(99.9%) 0.017 ms/op
Iteration   1: 3.540 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.738 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   4.116 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.005 ms/op
                 createUser·p0.999:  21.618 ms/op
                 createUser·p0.9999: 24.542 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   2: 3.539 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  23.188 ms/op
                 createUser·p0.9999: 26.115 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   3: 3.564 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   3.383 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  22.329 ms/op
                 createUser·p0.9999: 28.051 ms/op
                 createUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 270467
  mean =      3.548 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5104 
    [ 2.500,  5.000) = 257569 
    [ 5.000,  7.500) = 6276 
    [ 7.500, 10.000) = 865 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 182 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.388 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     22.118 ms/op
     p(99.9900) =     26.508 ms/op
     p(99.9990) =     28.377 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 8.666 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.012 ms/op
Iteration   1: 3.410 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.452 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.166 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  20.283 ms/op
                 existUser·p0.9999: 24.674 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   2: 3.435 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.711 ms/op
                 existUser·p0.95:   4.145 ms/op
                 existUser·p0.99:   6.799 ms/op
                 existUser·p0.999:  23.027 ms/op
                 existUser·p0.9999: 29.678 ms/op
                 existUser·p1.00:   30.179 ms/op

Iteration   3: 3.431 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.307 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.186 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  12.367 ms/op
                 existUser·p0.9999: 27.951 ms/op
                 existUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280183
  mean =      3.425 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9930 
    [ 2.500,  5.000) = 262482 
    [ 5.000,  7.500) = 6683 
    [ 7.500, 10.000) = 508 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 43 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.588 ms/op
     p(99.9000) =     17.066 ms/op
     p(99.9900) =     28.506 ms/op
     p(99.9990) =     30.120 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


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
# Warmup Iteration   1: 10.948 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.009 ms/op
Iteration   1: 3.577 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   5.169 ms/op
                 getUser·p0.99:   7.766 ms/op
                 getUser·p0.999:  23.462 ms/op
                 getUser·p0.9999: 25.957 ms/op
                 getUser·p1.00:   47.841 ms/op

Iteration   2: 3.534 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.272 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   6.996 ms/op
                 getUser·p0.999:  23.215 ms/op
                 getUser·p0.9999: 26.082 ms/op
                 getUser·p1.00:   26.509 ms/op

Iteration   3: 3.481 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.520 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  14.270 ms/op
                 getUser·p0.9999: 27.853 ms/op
                 getUser·p1.00:   28.934 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271917
  mean =      3.530 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 262005 
    [ 5.000, 10.000) = 9127 
    [10.000, 15.000) = 447 
    [15.000, 20.000) = 42 
    [20.000, 25.000) = 161 
    [25.000, 30.000) = 134 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     22.905 ms/op
     p(99.9900) =     26.996 ms/op
     p(99.9990) =     28.943 ms/op
     p(99.9999) =     47.841 ms/op
    p(100.0000) =     47.841 ms/op


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
# Warmup Iteration   1: 11.307 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.868 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.349 ±(99.9%) 0.015 ms/op
Iteration   1: 4.307 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   4.104 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   8.315 ms/op
                 listUser·p0.999:  23.888 ms/op
                 listUser·p0.9999: 31.924 ms/op
                 listUser·p1.00:   32.571 ms/op

Iteration   2: 4.223 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.939 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   8.024 ms/op
                 listUser·p0.999:  15.966 ms/op
                 listUser·p0.9999: 44.105 ms/op
                 listUser·p1.00:   47.055 ms/op

Iteration   3: 4.198 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   4.030 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  17.891 ms/op
                 listUser·p0.9999: 19.346 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 226277
  mean =      4.242 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 213879 
    [ 5.000, 10.000) = 11272 
    [10.000, 15.000) = 605 
    [15.000, 20.000) = 357 
    [20.000, 25.000) = 91 
    [25.000, 30.000) = 21 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 11 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.249 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.095 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     32.551 ms/op
     p(99.9990) =     46.741 ms/op
     p(99.9999) =     47.055 ms/op
    p(100.0000) =     47.055 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.838 ± 2.266  ops/ms
ClientPb.existUser                       thrpt       3   9.323 ± 4.439  ops/ms
ClientPb.getUser                         thrpt       3   8.955 ± 2.776  ops/ms
ClientPb.listUser                        thrpt       3   7.485 ± 4.384  ops/ms
ClientPb.createUser                       avgt       3   3.599 ± 0.654   ms/op
ClientPb.existUser                        avgt       3   3.387 ± 1.068   ms/op
ClientPb.getUser                          avgt       3   3.555 ± 1.542   ms/op
ClientPb.listUser                         avgt       3   4.184 ± 0.339   ms/op
ClientPb.createUser                     sample  270467   3.548 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.738           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.379           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.388           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.742           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.118           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.508           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.475           ms/op
ClientPb.existUser                      sample  280183   3.425 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.208           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.330           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.170           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.588           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.066           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.506           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.179           ms/op
ClientPb.getUser                        sample  271917   3.530 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.057           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.367           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.887           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.127           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.905           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.996           ms/op
ClientPb.getUser:getUser·p1.00          sample          47.841           ms/op
ClientPb.listUser                       sample  226277   4.242 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.249           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.063           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.095           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.389           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.579           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.551           ms/op
ClientPb.listUser:listUser·p1.00        sample          47.055           ms/op
