# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.508 ops/ms
# Warmup Iteration   2: 12.061 ops/ms
# Warmup Iteration   3: 12.353 ops/ms
Iteration   1: 12.560 ops/ms
Iteration   2: 12.525 ops/ms
Iteration   3: 12.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.550 ±(99.9%) 0.397 ops/ms [Average]
  (min, avg, max) = (12.525, 12.550, 12.565), stdev = 0.022
  CI (99.9%): [12.153, 12.947] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 8.212 ops/ms
# Warmup Iteration   2: 12.992 ops/ms
# Warmup Iteration   3: 12.898 ops/ms
Iteration   1: 12.833 ops/ms
Iteration   2: 12.844 ops/ms
Iteration   3: 12.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.873 ±(99.9%) 1.090 ops/ms [Average]
  (min, avg, max) = (12.833, 12.873, 12.941), stdev = 0.060
  CI (99.9%): [11.783, 13.962] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.859 ops/ms
# Warmup Iteration   2: 12.723 ops/ms
# Warmup Iteration   3: 12.725 ops/ms
Iteration   1: 12.980 ops/ms
Iteration   2: 12.945 ops/ms
Iteration   3: 12.859 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.928 ±(99.9%) 1.140 ops/ms [Average]
  (min, avg, max) = (12.859, 12.928, 12.980), stdev = 0.062
  CI (99.9%): [11.788, 14.068] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.347 ops/ms
# Warmup Iteration   2: 10.258 ops/ms
# Warmup Iteration   3: 10.442 ops/ms
Iteration   1: 10.411 ops/ms
Iteration   2: 10.377 ops/ms
Iteration   3: 10.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.404 ±(99.9%) 0.446 ops/ms [Average]
  (min, avg, max) = (10.377, 10.404, 10.425), stdev = 0.024
  CI (99.9%): [9.958, 10.851] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.121 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.598 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.536 ±(99.9%) 0.003 ms/op
Iteration   1: 2.558 ±(99.9%) 0.004 ms/op
Iteration   2: 2.562 ±(99.9%) 0.005 ms/op
Iteration   3: 2.552 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.557 ±(99.9%) 0.091 ms/op [Average]
  (min, avg, max) = (2.552, 2.557, 2.562), stdev = 0.005
  CI (99.9%): [2.466, 2.649] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.690 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.469 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.003 ms/op
Iteration   1: 2.464 ±(99.9%) 0.003 ms/op
Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
Iteration   3: 2.444 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.462 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (2.444, 2.462, 2.476), stdev = 0.016
  CI (99.9%): [2.168, 2.756] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.802 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.004 ms/op
Iteration   1: 2.504 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.497 ±(99.9%) 0.122 ms/op [Average]
  (min, avg, max) = (2.492, 2.497, 2.504), stdev = 0.007
  CI (99.9%): [2.375, 2.619] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.978 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.005 ms/op
Iteration   1: 3.073 ±(99.9%) 0.004 ms/op
Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
Iteration   3: 3.049 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.063 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (3.049, 3.063, 3.073), stdev = 0.012
  CI (99.9%): [2.838, 3.288] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.090 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.683 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.567 ±(99.9%) 0.006 ms/op
Iteration   1: 2.569 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   2.654 ms/op
                 createUser·p0.90:   3.113 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.055 ms/op
                 createUser·p0.999:  12.173 ms/op
                 createUser·p0.9999: 17.123 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   2: 2.557 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   2.646 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  10.043 ms/op
                 createUser·p0.9999: 13.066 ms/op
                 createUser·p1.00:   13.697 ms/op

Iteration   3: 2.570 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   4.018 ms/op
                 createUser·p0.999:  8.742 ms/op
                 createUser·p0.9999: 11.789 ms/op
                 createUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 373915
  mean =      2.565 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 176774 
    [ 2.500,  3.750) = 191895 
    [ 3.750,  5.000) = 4132 
    [ 5.000,  6.250) = 616 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      2.638 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.248 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      8.931 ms/op
     p(99.9900) =     16.245 ms/op
     p(99.9990) =     17.254 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.837 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.715 ms/op
                 existUser·p0.999:  5.177 ms/op
                 existUser·p0.9999: 13.743 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  6.798 ms/op
                 existUser·p0.9999: 14.058 ms/op
                 existUser·p1.00:   15.335 ms/op

Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.964 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.031 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  8.985 ms/op
                 existUser·p0.9999: 12.124 ms/op
                 existUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388549
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 191757 
    [ 2.500,  3.750) = 193139 
    [ 3.750,  5.000) = 2925 
    [ 5.000,  6.250) = 292 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      2.998 ms/op
     p(95.0000) =      3.109 ms/op
     p(99.0000) =      3.703 ms/op
     p(99.9000) =      6.341 ms/op
     p(99.9900) =     13.571 ms/op
     p(99.9990) =     14.336 ms/op
     p(99.9999) =     15.335 ms/op
    p(100.0000) =     15.335 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.988 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.500 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  11.961 ms/op
                 getUser·p0.9999: 13.386 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   2: 2.515 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.727 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  9.106 ms/op
                 getUser·p0.9999: 14.062 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   3: 2.536 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.714 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.874 ms/op
                 getUser·p0.999:  8.339 ms/op
                 getUser·p0.9999: 10.915 ms/op
                 getUser·p1.00:   11.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381086
  mean =      2.517 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 188706 
    [ 2.500,  3.750) = 186109 
    [ 3.750,  5.000) = 4507 
    [ 5.000,  6.250) = 1246 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      4.166 ms/op
     p(99.9000) =      8.347 ms/op
     p(99.9900) =     13.335 ms/op
     p(99.9990) =     14.352 ms/op
     p(99.9999) =     14.533 ms/op
    p(100.0000) =     14.533 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.767 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.009 ms/op
Iteration   1: 3.055 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.814 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.823 ms/op
                 listUser·p0.999:  9.110 ms/op
                 listUser·p0.9999: 10.748 ms/op
                 listUser·p1.00:   11.567 ms/op

Iteration   2: 3.076 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.755 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  10.306 ms/op
                 listUser·p0.9999: 12.039 ms/op
                 listUser·p1.00:   13.206 ms/op

Iteration   3: 3.083 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   3.015 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   5.825 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 11.551 ms/op
                 listUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312255
  mean =      3.072 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 84019 
    [ 2.500,  3.750) = 184747 
    [ 3.750,  5.000) = 34385 
    [ 5.000,  6.250) = 7251 
    [ 6.250,  7.500) = 1032 
    [ 7.500,  8.750) = 258 
    [ 8.750, 10.000) = 234 
    [10.000, 11.250) = 153 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     11.567 ms/op
     p(99.9990) =     13.128 ms/op
     p(99.9999) =     13.206 ms/op
    p(100.0000) =     13.206 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.550 ± 0.397  ops/ms
ClientPb.existUser                       thrpt       3  12.873 ± 1.090  ops/ms
ClientPb.getUser                         thrpt       3  12.928 ± 1.140  ops/ms
ClientPb.listUser                        thrpt       3  10.404 ± 0.446  ops/ms
ClientPb.createUser                       avgt       3   2.557 ± 0.091   ms/op
ClientPb.existUser                        avgt       3   2.462 ± 0.294   ms/op
ClientPb.getUser                          avgt       3   2.497 ± 0.122   ms/op
ClientPb.listUser                         avgt       3   3.063 ± 0.225   ms/op
ClientPb.createUser                     sample  373915   2.565 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.822           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.638           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.248           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.931           ms/op
ClientPb.createUser:createUser·p0.9999  sample          16.245           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.465           ms/op
ClientPb.existUser                      sample  388549   2.468 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.880           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.109           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.341           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.571           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.335           ms/op
ClientPb.getUser                        sample  381086   2.517 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.714           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.347           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.335           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.533           ms/op
ClientPb.listUser                       sample  312255   3.072 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.755           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.985           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.800           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.567           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.206           ms/op
