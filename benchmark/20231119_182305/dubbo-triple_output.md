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
# Warmup Iteration   1: 4.584 ops/ms
# Warmup Iteration   2: 12.135 ops/ms
# Warmup Iteration   3: 12.397 ops/ms
Iteration   1: 12.621 ops/ms
Iteration   2: 12.645 ops/ms
Iteration   3: 12.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.662 ±(99.9%) 0.950 ops/ms [Average]
  (min, avg, max) = (12.621, 12.662, 12.721), stdev = 0.052
  CI (99.9%): [11.712, 13.612] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.762 ops/ms
# Warmup Iteration   2: 12.913 ops/ms
# Warmup Iteration   3: 13.024 ops/ms
Iteration   1: 13.131 ops/ms
Iteration   2: 12.946 ops/ms
Iteration   3: 13.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.040 ±(99.9%) 1.686 ops/ms [Average]
  (min, avg, max) = (12.946, 13.040, 13.131), stdev = 0.092
  CI (99.9%): [11.354, 14.726] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.793 ops/ms
# Warmup Iteration   2: 12.410 ops/ms
# Warmup Iteration   3: 12.587 ops/ms
Iteration   1: 12.732 ops/ms
Iteration   2: 12.601 ops/ms
Iteration   3: 12.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.638 ±(99.9%) 1.498 ops/ms [Average]
  (min, avg, max) = (12.581, 12.638, 12.732), stdev = 0.082
  CI (99.9%): [11.139, 14.136] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.496 ops/ms
# Warmup Iteration   2: 10.209 ops/ms
# Warmup Iteration   3: 10.409 ops/ms
Iteration   1: 10.338 ops/ms
Iteration   2: 10.213 ops/ms
Iteration   3: 10.343 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.298 ±(99.9%) 1.343 ops/ms [Average]
  (min, avg, max) = (10.213, 10.298, 10.343), stdev = 0.074
  CI (99.9%): [8.955, 11.642] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.113 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.578 ±(99.9%) 0.004 ms/op
Iteration   1: 2.588 ±(99.9%) 0.004 ms/op
Iteration   2: 2.563 ±(99.9%) 0.003 ms/op
Iteration   3: 2.555 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.569 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (2.555, 2.569, 2.588), stdev = 0.017
  CI (99.9%): [2.254, 2.884] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.999 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.003 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.452 ±(99.9%) 0.004 ms/op
Iteration   3: 2.458 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.458 ±(99.9%) 0.107 ms/op [Average]
  (min, avg, max) = (2.452, 2.458, 2.464), stdev = 0.006
  CI (99.9%): [2.351, 2.565] (assumes normal distribution)


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.579 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.004 ms/op
Iteration   1: 2.556 ±(99.9%) 0.004 ms/op
Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
Iteration   3: 2.554 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.546 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (2.530, 2.546, 2.556), stdev = 0.015
  CI (99.9%): [2.282, 2.811] (assumes normal distribution)


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
# Warmup Iteration   1: 4.717 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.005 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
Iteration   2: 3.061 ±(99.9%) 0.005 ms/op
Iteration   3: 3.046 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.055 ±(99.9%) 0.147 ms/op [Average]
  (min, avg, max) = (3.046, 3.055, 3.061), stdev = 0.008
  CI (99.9%): [2.908, 3.202] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.185 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.671 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.566 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  11.143 ms/op
                 createUser·p0.9999: 14.604 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   2: 2.528 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.987 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.684 ms/op
                 createUser·p0.999:  10.813 ms/op
                 createUser·p0.9999: 18.121 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.886 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.928 ms/op
                 createUser·p0.999:  8.765 ms/op
                 createUser·p0.9999: 11.123 ms/op
                 createUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379287
  mean =      2.529 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 34 
    [ 1.250,  2.500) = 180479 
    [ 2.500,  3.750) = 194407 
    [ 3.750,  5.000) = 3270 
    [ 5.000,  6.250) = 554 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     15.401 ms/op
     p(99.9990) =     18.888 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.740 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.468 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.436 ±(99.9%) 0.005 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.641 ms/op
                 existUser·p0.999:  6.395 ms/op
                 existUser·p0.9999: 13.353 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  6.101 ms/op
                 existUser·p0.9999: 12.554 ms/op
                 existUser·p1.00:   12.845 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.802 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.887 ms/op
                 existUser·p0.999:  9.421 ms/op
                 existUser·p0.9999: 16.978 ms/op
                 existUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387807
  mean =      2.473 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 190496 
    [ 2.500,  3.750) = 193298 
    [ 3.750,  5.000) = 3216 
    [ 5.000,  6.250) = 319 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      7.391 ms/op
     p(99.9900) =     13.475 ms/op
     p(99.9990) =     18.333 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.135 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.154 ms/op
                 getUser·p0.99:   3.596 ms/op
                 getUser·p0.999:  12.001 ms/op
                 getUser·p0.9999: 14.107 ms/op
                 getUser·p1.00:   15.057 ms/op

Iteration   2: 2.538 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.244 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  9.535 ms/op
                 getUser·p0.9999: 13.435 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   3: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.956 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.912 ms/op
                 getUser·p0.999:  8.731 ms/op
                 getUser·p0.9999: 11.518 ms/op
                 getUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381888
  mean =      2.512 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 187191 
    [ 2.500,  3.750) = 189012 
    [ 3.750,  5.000) = 3800 
    [ 5.000,  6.250) = 1282 
    [ 6.250,  7.500) = 116 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      4.080 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     13.923 ms/op
     p(99.9990) =     14.489 ms/op
     p(99.9999) =     15.057 ms/op
    p(100.0000) =     15.057 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.799 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.009 ms/op
Iteration   1: 3.067 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.744 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.980 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  8.794 ms/op
                 listUser·p0.9999: 11.537 ms/op
                 listUser·p1.00:   12.370 ms/op

Iteration   2: 3.061 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.831 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.765 ms/op
                 listUser·p0.9999: 11.897 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   3: 3.078 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  8.700 ms/op
                 listUser·p0.9999: 10.887 ms/op
                 listUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312593
  mean =      3.068 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 84330 
    [ 2.500,  3.750) = 184606 
    [ 3.750,  5.000) = 35090 
    [ 5.000,  6.250) = 6898 
    [ 6.250,  7.500) = 890 
    [ 7.500,  8.750) = 305 
    [ 8.750, 10.000) = 197 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     11.481 ms/op
     p(99.9990) =     12.224 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.662 ± 0.950  ops/ms
ClientPb.existUser                       thrpt       3  13.040 ± 1.686  ops/ms
ClientPb.getUser                         thrpt       3  12.638 ± 1.498  ops/ms
ClientPb.listUser                        thrpt       3  10.298 ± 1.343  ops/ms
ClientPb.createUser                       avgt       3   2.569 ± 0.315   ms/op
ClientPb.existUser                        avgt       3   2.458 ± 0.107   ms/op
ClientPb.getUser                          avgt       3   2.546 ± 0.265   ms/op
ClientPb.listUser                         avgt       3   3.055 ± 0.147   ms/op
ClientPb.createUser                     sample  379287   2.529 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.886           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.838           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.503           ms/op
ClientPb.createUser:createUser·p0.9999  sample          15.401           ms/op
ClientPb.createUser:createUser·p1.00    sample          19.366           ms/op
ClientPb.existUser                      sample  387807   2.473 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.793           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.391           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.475           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.776           ms/op
ClientPb.getUser                        sample  381888   2.512 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.731           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.191           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.080           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.241           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.923           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.057           ms/op
ClientPb.listUser                       sample  312593   3.068 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.744           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.006           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.977           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.044           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.481           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.534           ms/op
