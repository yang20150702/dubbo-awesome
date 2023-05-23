# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.099 ops/ms
# Warmup Iteration   2: 5.808 ops/ms
# Warmup Iteration   3: 8.649 ops/ms
Iteration   1: 9.399 ops/ms
Iteration   2: 9.385 ops/ms
Iteration   3: 9.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.398 ±(99.9%) 0.209 ops/ms [Average]
  (min, avg, max) = (9.385, 9.398, 9.408), stdev = 0.011
  CI (99.9%): [9.189, 9.606] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.206 ops/ms
# Warmup Iteration   2: 8.709 ops/ms
# Warmup Iteration   3: 9.811 ops/ms
Iteration   1: 9.445 ops/ms
Iteration   2: 9.548 ops/ms
Iteration   3: 9.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.529 ±(99.9%) 1.390 ops/ms [Average]
  (min, avg, max) = (9.445, 9.529, 9.594), stdev = 0.076
  CI (99.9%): [8.139, 10.919] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.058 ops/ms
# Warmup Iteration   2: 8.437 ops/ms
# Warmup Iteration   3: 9.146 ops/ms
Iteration   1: 9.607 ops/ms
Iteration   2: 9.365 ops/ms
Iteration   3: 9.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.503 ±(99.9%) 2.273 ops/ms [Average]
  (min, avg, max) = (9.365, 9.503, 9.607), stdev = 0.125
  CI (99.9%): [7.230, 11.777] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.827 ops/ms
# Warmup Iteration   2: 6.976 ops/ms
# Warmup Iteration   3: 8.093 ops/ms
Iteration   1: 8.006 ops/ms
Iteration   2: 8.149 ops/ms
Iteration   3: 8.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.163 ±(99.9%) 3.010 ops/ms [Average]
  (min, avg, max) = (8.006, 8.163, 8.335), stdev = 0.165
  CI (99.9%): [5.154, 11.173] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.063 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.009 ms/op
Iteration   1: 3.446 ±(99.9%) 0.009 ms/op
Iteration   2: 3.467 ±(99.9%) 0.007 ms/op
Iteration   3: 3.454 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.456 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (3.446, 3.456, 3.467), stdev = 0.010
  CI (99.9%): [3.269, 3.643] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.419 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.742 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.007 ms/op
Iteration   1: 3.279 ±(99.9%) 0.003 ms/op
Iteration   2: 3.408 ±(99.9%) 0.005 ms/op
Iteration   3: 3.290 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.326 ±(99.9%) 1.309 ms/op [Average]
  (min, avg, max) = (3.279, 3.326, 3.408), stdev = 0.072
  CI (99.9%): [2.017, 4.635] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 9.671 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.004 ms/op
Iteration   1: 3.370 ±(99.9%) 0.007 ms/op
Iteration   2: 3.375 ±(99.9%) 0.003 ms/op
Iteration   3: 3.385 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.377 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (3.370, 3.377, 3.385), stdev = 0.008
  CI (99.9%): [3.238, 3.516] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.144 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.459 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.013 ms/op
Iteration   1: 3.908 ±(99.9%) 0.014 ms/op
Iteration   2: 4.079 ±(99.9%) 0.013 ms/op
Iteration   3: 3.830 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.939 ±(99.9%) 2.323 ms/op [Average]
  (min, avg, max) = (3.830, 3.939, 4.079), stdev = 0.127
  CI (99.9%): [1.616, 6.262] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.688 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.010 ms/op
Iteration   1: 3.382 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   5.623 ms/op
                 createUser·p0.999:  18.263 ms/op
                 createUser·p0.9999: 20.793 ms/op
                 createUser·p1.00:   21.889 ms/op

Iteration   2: 3.431 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  19.508 ms/op
                 createUser·p0.9999: 23.921 ms/op
                 createUser·p1.00:   26.247 ms/op

Iteration   3: 3.464 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.438 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  19.774 ms/op
                 createUser·p0.9999: 26.469 ms/op
                 createUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280038
  mean =      3.425 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2157 
    [ 2.500,  5.000) = 271123 
    [ 5.000,  7.500) = 5745 
    [ 7.500, 10.000) = 537 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     26.994 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.529 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 3.620 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.358 ±(99.9%) 0.009 ms/op
Iteration   1: 3.361 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.323 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  19.751 ms/op
                 existUser·p0.9999: 31.796 ms/op
                 existUser·p1.00:   32.440 ms/op

Iteration   2: 3.330 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.642 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.985 ms/op
                 existUser·p0.99:   6.103 ms/op
                 existUser·p0.999:  22.428 ms/op
                 existUser·p0.9999: 25.539 ms/op
                 existUser·p1.00:   26.903 ms/op

Iteration   3: 3.382 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.949 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  9.142 ms/op
                 existUser·p0.9999: 26.135 ms/op
                 existUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285570
  mean =      3.357 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8144 
    [ 2.500,  5.000) = 271728 
    [ 5.000,  7.500) = 4509 
    [ 7.500, 10.000) = 844 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 47 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     16.941 ms/op
     p(99.9900) =     29.098 ms/op
     p(99.9990) =     32.291 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.439 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.540 ±(99.9%) 0.010 ms/op
Iteration   1: 3.615 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.489 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.129 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   6.996 ms/op
                 getUser·p0.999:  20.972 ms/op
                 getUser·p0.9999: 29.791 ms/op
                 getUser·p1.00:   31.228 ms/op

Iteration   2: 3.448 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.231 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  21.324 ms/op
                 getUser·p0.9999: 26.229 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   3: 3.448 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   5.884 ms/op
                 getUser·p0.999:  18.973 ms/op
                 getUser·p0.9999: 28.752 ms/op
                 getUser·p1.00:   31.654 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274133
  mean =      3.502 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5978 
    [ 2.500,  5.000) = 257922 
    [ 5.000,  7.500) = 9227 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     19.726 ms/op
     p(99.9900) =     29.000 ms/op
     p(99.9990) =     30.621 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.271 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.473 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.239 ±(99.9%) 0.014 ms/op
Iteration   1: 4.072 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   7.773 ms/op
                 listUser·p0.999:  20.775 ms/op
                 listUser·p0.9999: 23.405 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   2: 3.990 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  15.823 ms/op
                 listUser·p0.9999: 16.662 ms/op
                 listUser·p1.00:   17.760 ms/op

Iteration   3: 3.980 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  15.163 ms/op
                 listUser·p0.9999: 20.185 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239331
  mean =      4.013 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 228624 
    [ 5.000,  7.500) = 8092 
    [ 7.500, 10.000) = 1769 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 245 
    [15.000, 17.500) = 221 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      7.586 ms/op
     p(99.9000) =     15.942 ms/op
     p(99.9900) =     22.383 ms/op
     p(99.9990) =     24.386 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.398 ± 0.209  ops/ms
ClientPb.existUser                       thrpt       3   9.529 ± 1.390  ops/ms
ClientPb.getUser                         thrpt       3   9.503 ± 2.273  ops/ms
ClientPb.listUser                        thrpt       3   8.163 ± 3.010  ops/ms
ClientPb.createUser                       avgt       3   3.456 ± 0.187   ms/op
ClientPb.existUser                        avgt       3   3.326 ± 1.309   ms/op
ClientPb.getUser                          avgt       3   3.377 ± 0.139   ms/op
ClientPb.listUser                         avgt       3   3.939 ± 2.323   ms/op
ClientPb.createUser                     sample  280038   3.425 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.694           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.277           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.899           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.078           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.579           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.985           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.099           ms/op
ClientPb.existUser                      sample  285570   3.357 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.044           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.789           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.145           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.078           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.941           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.098           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.440           ms/op
ClientPb.getUser                        sample  274133   3.502 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.231           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.346           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.668           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.726           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.000           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.654           ms/op
ClientPb.listUser                       sample  239331   4.013 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.210           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.882           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.586           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.942           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.383           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.740           ms/op
