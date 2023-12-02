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
# Warmup Iteration   1: 4.846 ops/ms
# Warmup Iteration   2: 12.152 ops/ms
# Warmup Iteration   3: 12.481 ops/ms
Iteration   1: 12.771 ops/ms
Iteration   2: 12.722 ops/ms
Iteration   3: 12.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.720 ±(99.9%) 0.950 ops/ms [Average]
  (min, avg, max) = (12.667, 12.720, 12.771), stdev = 0.052
  CI (99.9%): [11.770, 13.670] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.757 ops/ms
# Warmup Iteration   2: 12.981 ops/ms
# Warmup Iteration   3: 12.999 ops/ms
Iteration   1: 12.607 ops/ms
Iteration   2: 12.882 ops/ms
Iteration   3: 12.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.792 ±(99.9%) 2.931 ops/ms [Average]
  (min, avg, max) = (12.607, 12.792, 12.888), stdev = 0.161
  CI (99.9%): [9.861, 15.723] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.526 ops/ms
# Warmup Iteration   2: 11.925 ops/ms
# Warmup Iteration   3: 12.196 ops/ms
Iteration   1: 12.467 ops/ms
Iteration   2: 12.658 ops/ms
Iteration   3: 12.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.523 ±(99.9%) 2.134 ops/ms [Average]
  (min, avg, max) = (12.445, 12.523, 12.658), stdev = 0.117
  CI (99.9%): [10.389, 14.657] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.270 ops/ms
# Warmup Iteration   2: 10.293 ops/ms
# Warmup Iteration   3: 10.796 ops/ms
Iteration   1: 10.572 ops/ms
Iteration   2: 10.476 ops/ms
Iteration   3: 10.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.565 ±(99.9%) 1.566 ops/ms [Average]
  (min, avg, max) = (10.476, 10.565, 10.647), stdev = 0.086
  CI (99.9%): [8.999, 12.131] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.093 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.698 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.577 ±(99.9%) 0.009 ms/op
Iteration   1: 2.543 ±(99.9%) 0.008 ms/op
Iteration   2: 2.559 ±(99.9%) 0.010 ms/op
Iteration   3: 2.606 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.569 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (2.543, 2.569, 2.606), stdev = 0.033
  CI (99.9%): [1.967, 3.171] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.744 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.433 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.441 ±(99.9%) 0.008 ms/op
Iteration   1: 2.403 ±(99.9%) 0.005 ms/op
Iteration   2: 2.395 ±(99.9%) 0.005 ms/op
Iteration   3: 2.397 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.399 ±(99.9%) 0.080 ms/op [Average]
  (min, avg, max) = (2.395, 2.399, 2.403), stdev = 0.004
  CI (99.9%): [2.319, 2.478] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.946 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.607 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.578 ±(99.9%) 0.007 ms/op
Iteration   1: 2.764 ±(99.9%) 0.009 ms/op
Iteration   2: 2.650 ±(99.9%) 0.007 ms/op
Iteration   3: 2.575 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.663 ±(99.9%) 1.737 ms/op [Average]
  (min, avg, max) = (2.575, 2.663, 2.764), stdev = 0.095
  CI (99.9%): [0.926, 4.399] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 5.068 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.012 ms/op
Iteration   1: 3.242 ±(99.9%) 0.011 ms/op
Iteration   2: 3.278 ±(99.9%) 0.015 ms/op
Iteration   3: 3.019 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.180 ±(99.9%) 2.557 ms/op [Average]
  (min, avg, max) = (3.019, 3.180, 3.278), stdev = 0.140
  CI (99.9%): [0.623, 5.736] (assumes normal distribution)


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
# Warmup Iteration   1: 4.732 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 2.814 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.583 ±(99.9%) 0.007 ms/op
Iteration   1: 2.663 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.487 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   5.308 ms/op
                 createUser·p0.999:  12.729 ms/op
                 createUser·p0.9999: 18.316 ms/op
                 createUser·p1.00:   19.104 ms/op

Iteration   2: 2.576 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   2.527 ms/op
                 createUser·p0.90:   3.355 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  11.367 ms/op
                 createUser·p0.9999: 16.576 ms/op
                 createUser·p1.00:   17.695 ms/op

Iteration   3: 2.557 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.353 ms/op
                 createUser·p0.50:   2.511 ms/op
                 createUser·p0.90:   3.305 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.666 ms/op
                 createUser·p0.999:  11.647 ms/op
                 createUser·p0.9999: 16.326 ms/op
                 createUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 369178
  mean =      2.598 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 522 
    [ 1.250,  2.500) = 176585 
    [ 2.500,  3.750) = 172634 
    [ 3.750,  5.000) = 16226 
    [ 5.000,  6.250) = 1644 
    [ 6.250,  7.500) = 608 
    [ 7.500,  8.750) = 339 
    [ 8.750, 10.000) = 126 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 80 
    [16.250, 17.500) = 57 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.353 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =     11.649 ms/op
     p(99.9900) =     16.813 ms/op
     p(99.9990) =     18.751 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 3.886 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.586 ±(99.9%) 0.008 ms/op
Iteration   1: 2.504 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.423 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.858 ms/op
                 existUser·p0.999:  10.064 ms/op
                 existUser·p0.9999: 21.503 ms/op
                 existUser·p1.00:   21.823 ms/op

Iteration   2: 2.529 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.394 ms/op
                 existUser·p0.50:   2.441 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  13.078 ms/op
                 existUser·p0.9999: 20.831 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   3: 2.436 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.368 ms/op
                 existUser·p0.50:   2.388 ms/op
                 existUser·p0.90:   3.105 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  10.629 ms/op
                 existUser·p0.9999: 15.434 ms/op
                 existUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385399
  mean =      2.489 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 210482 
    [ 2.500,  5.000) = 171271 
    [ 5.000,  7.500) = 2707 
    [ 7.500, 10.000) = 497 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      2.421 ms/op
     p(90.0000) =      3.207 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.915 ms/op
     p(99.9000) =     10.908 ms/op
     p(99.9900) =     20.775 ms/op
     p(99.9990) =     21.823 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 4.239 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.543 ±(99.9%) 0.007 ms/op
Iteration   1: 2.554 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.520 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.318 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  12.966 ms/op
                 getUser·p0.9999: 14.770 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   2: 2.521 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.410 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   3.215 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  12.801 ms/op
                 getUser·p0.9999: 18.088 ms/op
                 getUser·p1.00:   19.300 ms/op

Iteration   3: 2.566 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.429 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.293 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   5.071 ms/op
                 getUser·p0.999:  10.607 ms/op
                 getUser·p0.9999: 18.877 ms/op
                 getUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376622
  mean =      2.547 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 191038 
    [ 2.500,  5.000) = 182365 
    [ 5.000,  7.500) = 2402 
    [ 7.500, 10.000) = 324 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 226 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.410 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.841 ms/op
     p(99.9000) =     11.825 ms/op
     p(99.9900) =     17.804 ms/op
     p(99.9990) =     20.038 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 5.132 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.012 ms/op
Iteration   1: 3.064 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.510 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   6.267 ms/op
                 listUser·p0.999:  12.444 ms/op
                 listUser·p0.9999: 16.175 ms/op
                 listUser·p1.00:   20.939 ms/op

Iteration   2: 3.053 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.373 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.882 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  12.897 ms/op
                 listUser·p0.9999: 20.089 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 3.152 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.426 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  12.396 ms/op
                 listUser·p0.9999: 14.022 ms/op
                 listUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310500
  mean =      3.089 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 102505 
    [ 2.500,  5.000) = 195006 
    [ 5.000,  7.500) = 11059 
    [ 7.500, 10.000) = 1216 
    [10.000, 12.500) = 411 
    [12.500, 15.000) = 202 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     12.427 ms/op
     p(99.9900) =     19.323 ms/op
     p(99.9990) =     21.184 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.720 ± 0.950  ops/ms
ClientPb.existUser                       thrpt       3  12.792 ± 2.931  ops/ms
ClientPb.getUser                         thrpt       3  12.523 ± 2.134  ops/ms
ClientPb.listUser                        thrpt       3  10.565 ± 1.566  ops/ms
ClientPb.createUser                       avgt       3   2.569 ± 0.602   ms/op
ClientPb.existUser                        avgt       3   2.399 ± 0.080   ms/op
ClientPb.getUser                          avgt       3   2.663 ± 1.737   ms/op
ClientPb.listUser                         avgt       3   3.180 ± 2.557   ms/op
ClientPb.createUser                     sample  369178   2.598 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.353           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.540           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.858           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.649           ms/op
ClientPb.createUser:createUser·p0.9999  sample          16.813           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.104           ms/op
ClientPb.existUser                      sample  385399   2.489 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.368           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.421           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.99      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.908           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.775           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.889           ms/op
ClientPb.getUser                        sample  376622   2.547 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.410           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.690           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.841           ms/op
ClientPb.getUser:getUser·p0.999         sample          11.825           ms/op
ClientPb.getUser:getUser·p0.9999        sample          17.804           ms/op
ClientPb.getUser:getUser·p1.00          sample          21.627           ms/op
ClientPb.listUser                       sample  310500   3.089 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.373           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.841           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.668           ms/op
ClientPb.listUser:listUser·p0.999       sample          12.427           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.323           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.065           ms/op
