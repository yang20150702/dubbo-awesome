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
# Warmup Iteration   1: 2.314 ops/ms
# Warmup Iteration   2: 6.168 ops/ms
# Warmup Iteration   3: 9.045 ops/ms
Iteration   1: 8.995 ops/ms
Iteration   2: 9.203 ops/ms
Iteration   3: 9.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.104 ±(99.9%) 1.904 ops/ms [Average]
  (min, avg, max) = (8.995, 9.104, 9.203), stdev = 0.104
  CI (99.9%): [7.200, 11.008] (assumes normal distribution)


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
# Warmup Iteration   1: 2.904 ops/ms
# Warmup Iteration   2: 8.859 ops/ms
# Warmup Iteration   3: 9.580 ops/ms
Iteration   1: 10.083 ops/ms
Iteration   2: 9.723 ops/ms
Iteration   3: 9.872 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.893 ±(99.9%) 3.298 ops/ms [Average]
  (min, avg, max) = (9.723, 9.893, 10.083), stdev = 0.181
  CI (99.9%): [6.594, 13.191] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.393 ops/ms
# Warmup Iteration   2: 8.679 ops/ms
# Warmup Iteration   3: 9.103 ops/ms
Iteration   1: 9.551 ops/ms
Iteration   2: 9.661 ops/ms
Iteration   3: 9.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.518 ±(99.9%) 2.961 ops/ms [Average]
  (min, avg, max) = (9.341, 9.518, 9.661), stdev = 0.162
  CI (99.9%): [6.556, 12.479] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.629 ops/ms
# Warmup Iteration   2: 7.303 ops/ms
# Warmup Iteration   3: 8.110 ops/ms
Iteration   1: 8.252 ops/ms
Iteration   2: 7.863 ops/ms
Iteration   3: 8.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.152 ±(99.9%) 4.655 ops/ms [Average]
  (min, avg, max) = (7.863, 8.152, 8.343), stdev = 0.255
  CI (99.9%): [3.497, 12.808] (assumes normal distribution)


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
# Warmup Iteration   1: 10.404 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.878 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.011 ms/op
Iteration   1: 3.356 ±(99.9%) 0.004 ms/op
Iteration   2: 3.326 ±(99.9%) 0.011 ms/op
Iteration   3: 3.339 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.340 ±(99.9%) 0.273 ms/op [Average]
  (min, avg, max) = (3.326, 3.340, 3.356), stdev = 0.015
  CI (99.9%): [3.067, 3.613] (assumes normal distribution)


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
# Warmup Iteration   1: 8.344 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.589 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.004 ms/op
Iteration   1: 3.212 ±(99.9%) 0.006 ms/op
Iteration   2: 3.210 ±(99.9%) 0.010 ms/op
Iteration   3: 3.335 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.252 ±(99.9%) 1.314 ms/op [Average]
  (min, avg, max) = (3.210, 3.252, 3.335), stdev = 0.072
  CI (99.9%): [1.938, 4.566] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.852 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.008 ms/op
Iteration   1: 3.374 ±(99.9%) 0.007 ms/op
Iteration   2: 3.253 ±(99.9%) 0.009 ms/op
Iteration   3: 3.253 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.294 ±(99.9%) 1.275 ms/op [Average]
  (min, avg, max) = (3.253, 3.294, 3.374), stdev = 0.070
  CI (99.9%): [2.018, 4.569] (assumes normal distribution)


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
# Warmup Iteration   1: 10.344 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.435 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.010 ms/op
Iteration   1: 3.941 ±(99.9%) 0.008 ms/op
Iteration   2: 3.793 ±(99.9%) 0.012 ms/op
Iteration   3: 3.829 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.855 ±(99.9%) 1.403 ms/op [Average]
  (min, avg, max) = (3.793, 3.855, 3.941), stdev = 0.077
  CI (99.9%): [2.452, 5.257] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.123 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.385 ±(99.9%) 0.011 ms/op
Iteration   1: 3.317 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  16.342 ms/op
                 createUser·p0.9999: 26.018 ms/op
                 createUser·p1.00:   26.411 ms/op

Iteration   2: 3.341 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.630 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  21.632 ms/op
                 createUser·p0.9999: 24.622 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   3: 3.278 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.017 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  13.643 ms/op
                 createUser·p0.9999: 24.085 ms/op
                 createUser·p1.00:   25.068 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 289776
  mean =      3.312 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18231 
    [ 2.500,  5.000) = 266120 
    [ 5.000,  7.500) = 4687 
    [ 7.500, 10.000) = 399 
    [10.000, 12.500) = 44 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 154 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =     13.134 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     26.316 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 8.212 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.008 ms/op
Iteration   1: 3.191 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.305 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  9.880 ms/op
                 existUser·p0.9999: 22.183 ms/op
                 existUser·p1.00:   22.905 ms/op

Iteration   2: 3.271 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.487 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.890 ms/op
                 existUser·p0.999:  17.503 ms/op
                 existUser·p0.9999: 24.861 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   3: 3.277 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.395 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   5.799 ms/op
                 existUser·p0.999:  12.571 ms/op
                 existUser·p0.9999: 26.214 ms/op
                 existUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 295666
  mean =      3.246 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15309 
    [ 2.500,  5.000) = 275291 
    [ 5.000,  7.500) = 4037 
    [ 7.500, 10.000) = 533 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     13.555 ms/op
     p(99.9900) =     25.606 ms/op
     p(99.9990) =     26.511 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.373 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.009 ms/op
Iteration   1: 3.430 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  19.333 ms/op
                 getUser·p0.9999: 22.894 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   2: 3.425 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.915 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  23.221 ms/op
                 getUser·p0.9999: 28.639 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   3: 3.374 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.677 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  21.952 ms/op
                 getUser·p0.9999: 26.804 ms/op
                 getUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281385
  mean =      3.410 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1713 
    [ 2.500,  5.000) = 269995 
    [ 5.000,  7.500) = 8486 
    [ 7.500, 10.000) = 611 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.268 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     20.283 ms/op
     p(99.9900) =     28.143 ms/op
     p(99.9990) =     28.991 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.748 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 4.679 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.013 ms/op
Iteration   1: 4.149 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.540 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  18.272 ms/op
                 listUser·p0.9999: 23.120 ms/op
                 listUser·p1.00:   24.150 ms/op

Iteration   2: 4.019 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.894 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.907 ms/op
                 listUser·p0.99:   7.094 ms/op
                 listUser·p0.999:  15.581 ms/op
                 listUser·p0.9999: 17.859 ms/op
                 listUser·p1.00:   18.022 ms/op

Iteration   3: 3.894 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.348 ms/op
                 listUser·p0.999:  13.533 ms/op
                 listUser·p0.9999: 19.268 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238888
  mean =      4.018 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 227692 
    [ 5.000,  7.500) = 8445 
    [ 7.500, 10.000) = 1904 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.540 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     22.093 ms/op
     p(99.9990) =     24.072 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.104 ± 1.904  ops/ms
ClientPb.existUser                       thrpt       3   9.893 ± 3.298  ops/ms
ClientPb.getUser                         thrpt       3   9.518 ± 2.961  ops/ms
ClientPb.listUser                        thrpt       3   8.152 ± 4.655  ops/ms
ClientPb.createUser                       avgt       3   3.340 ± 0.273   ms/op
ClientPb.existUser                        avgt       3   3.252 ± 1.314   ms/op
ClientPb.getUser                          avgt       3   3.294 ± 1.275   ms/op
ClientPb.listUser                         avgt       3   3.855 ± 1.403   ms/op
ClientPb.createUser                     sample  289776   3.312 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.017           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.527           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.620           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.134           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.969           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.411           ms/op
ClientPb.existUser                      sample  295666   3.246 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.305           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.178           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.555           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.606           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.640           ms/op
ClientPb.getUser                        sample  281385   3.410 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.268           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.038           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.283           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.143           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.360           ms/op
ClientPb.listUser                       sample  238888   4.018 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.540           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.923           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.692           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.581           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.093           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.150           ms/op
