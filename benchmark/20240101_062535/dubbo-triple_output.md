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
# Warmup Iteration   1: 4.693 ops/ms
# Warmup Iteration   2: 11.669 ops/ms
# Warmup Iteration   3: 12.058 ops/ms
Iteration   1: 12.340 ops/ms
Iteration   2: 12.393 ops/ms
Iteration   3: 12.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.377 ±(99.9%) 0.587 ops/ms [Average]
  (min, avg, max) = (12.340, 12.377, 12.399), stdev = 0.032
  CI (99.9%): [11.791, 12.964] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.305 ops/ms
# Warmup Iteration   2: 12.749 ops/ms
# Warmup Iteration   3: 12.686 ops/ms
Iteration   1: 12.724 ops/ms
Iteration   2: 12.677 ops/ms
Iteration   3: 12.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.709 ±(99.9%) 0.522 ops/ms [Average]
  (min, avg, max) = (12.677, 12.709, 12.728), stdev = 0.029
  CI (99.9%): [12.188, 13.231] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.782 ops/ms
# Warmup Iteration   2: 12.360 ops/ms
# Warmup Iteration   3: 12.597 ops/ms
Iteration   1: 12.654 ops/ms
Iteration   2: 12.651 ops/ms
Iteration   3: 12.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.655 ±(99.9%) 0.105 ops/ms [Average]
  (min, avg, max) = (12.651, 12.655, 12.662), stdev = 0.006
  CI (99.9%): [12.551, 12.760] (assumes normal distribution)


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
# Warmup Iteration   1: 6.786 ops/ms
# Warmup Iteration   2: 10.465 ops/ms
# Warmup Iteration   3: 10.536 ops/ms
Iteration   1: 10.641 ops/ms
Iteration   2: 10.563 ops/ms
Iteration   3: 10.584 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.596 ±(99.9%) 0.740 ops/ms [Average]
  (min, avg, max) = (10.563, 10.596, 10.641), stdev = 0.041
  CI (99.9%): [9.856, 11.336] (assumes normal distribution)


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.569 ±(99.9%) 0.004 ms/op
Iteration   1: 2.588 ±(99.9%) 0.005 ms/op
Iteration   2: 2.601 ±(99.9%) 0.004 ms/op
Iteration   3: 2.566 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.585 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (2.566, 2.585, 2.601), stdev = 0.017
  CI (99.9%): [2.266, 2.904] (assumes normal distribution)


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.003 ms/op
Iteration   1: 2.481 ±(99.9%) 0.004 ms/op
Iteration   2: 2.465 ±(99.9%) 0.004 ms/op
Iteration   3: 2.499 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.482 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (2.465, 2.482, 2.499), stdev = 0.017
  CI (99.9%): [2.176, 2.788] (assumes normal distribution)


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
# Warmup Iteration   1: 3.723 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.004 ms/op
Iteration   1: 2.527 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.508 ±(99.9%) 0.350 ms/op [Average]
  (min, avg, max) = (2.489, 2.508, 2.527), stdev = 0.019
  CI (99.9%): [2.158, 2.859] (assumes normal distribution)


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
# Warmup Iteration   1: 4.791 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.005 ms/op
Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
Iteration   3: 3.045 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.052 ±(99.9%) 0.129 ms/op [Average]
  (min, avg, max) = (3.045, 3.052, 3.058), stdev = 0.007
  CI (99.9%): [2.923, 3.181] (assumes normal distribution)


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
# Warmup Iteration   1: 4.209 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.768 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
Iteration   1: 2.528 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.695 ms/op
                 createUser·p0.999:  11.386 ms/op
                 createUser·p0.9999: 14.608 ms/op
                 createUser·p1.00:   15.417 ms/op

Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.633 ms/op
                 createUser·p0.999:  10.112 ms/op
                 createUser·p0.9999: 11.835 ms/op
                 createUser·p1.00:   12.124 ms/op

Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.096 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.731 ms/op
                 createUser·p0.999:  9.044 ms/op
                 createUser·p0.9999: 10.221 ms/op
                 createUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378702
  mean =      2.532 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 181358 
    [ 2.500,  3.750) = 193955 
    [ 3.750,  5.000) = 2621 
    [ 5.000,  6.250) = 270 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 97 
    [11.250, 12.500) = 103 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      3.695 ms/op
     p(99.9000) =      9.065 ms/op
     p(99.9900) =     13.500 ms/op
     p(99.9990) =     15.333 ms/op
     p(99.9999) =     16.269 ms/op
    p(100.0000) =     16.269 ms/op


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.485 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.469 ms/op
                 existUser·p0.999:  7.966 ms/op
                 existUser·p0.9999: 13.593 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   2: 2.481 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.051 ms/op
                 existUser·p0.50:   2.613 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.478 ms/op
                 existUser·p0.999:  8.786 ms/op
                 existUser·p0.9999: 12.648 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.760 ms/op
                 existUser·p0.999:  7.195 ms/op
                 existUser·p0.9999: 11.718 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 385564
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 188280 
    [ 2.500,  3.750) = 194315 
    [ 3.750,  5.000) = 2124 
    [ 5.000,  6.250) = 355 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.019 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      8.412 ms/op
     p(99.9900) =     12.993 ms/op
     p(99.9990) =     13.861 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 3.996 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.590 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.524 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.838 ms/op
                 getUser·p0.999:  11.682 ms/op
                 getUser·p0.9999: 13.702 ms/op
                 getUser·p1.00:   14.238 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.112 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.809 ms/op
                 getUser·p0.999:  9.206 ms/op
                 getUser·p0.9999: 13.812 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   3: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  8.815 ms/op
                 getUser·p0.9999: 11.996 ms/op
                 getUser·p1.00:   12.714 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382339
  mean =      2.509 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 188193 
    [ 2.500,  3.750) = 189962 
    [ 3.750,  5.000) = 3457 
    [ 5.000,  6.250) = 255 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.972 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.793 ms/op
     p(99.9000) =      8.863 ms/op
     p(99.9900) =     13.677 ms/op
     p(99.9990) =     14.377 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


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
# Warmup Iteration   1: 4.775 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.008 ms/op
Iteration   1: 2.991 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.698 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.464 ms/op
                 listUser·p0.999:  9.011 ms/op
                 listUser·p0.9999: 10.827 ms/op
                 listUser·p1.00:   11.682 ms/op

Iteration   2: 2.959 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.954 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.768 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  9.404 ms/op
                 listUser·p0.9999: 10.620 ms/op
                 listUser·p1.00:   11.354 ms/op

Iteration   3: 2.990 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.803 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.562 ms/op
                 listUser·p0.999:  10.096 ms/op
                 listUser·p0.9999: 13.074 ms/op
                 listUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321887
  mean =      2.980 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 95237 
    [ 2.500,  3.750) = 189883 
    [ 3.750,  5.000) = 30381 
    [ 5.000,  6.250) = 5056 
    [ 6.250,  7.500) = 538 
    [ 7.500,  8.750) = 173 
    [ 8.750, 10.000) = 290 
    [10.000, 11.250) = 165 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.521 ms/op
     p(99.9900) =     11.679 ms/op
     p(99.9990) =     13.646 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.377 ± 0.587  ops/ms
ClientPb.existUser                       thrpt       3  12.709 ± 0.522  ops/ms
ClientPb.getUser                         thrpt       3  12.655 ± 0.105  ops/ms
ClientPb.listUser                        thrpt       3  10.596 ± 0.740  ops/ms
ClientPb.createUser                       avgt       3   2.585 ± 0.319   ms/op
ClientPb.existUser                        avgt       3   2.482 ± 0.306   ms/op
ClientPb.getUser                          avgt       3   2.508 ± 0.350   ms/op
ClientPb.listUser                         avgt       3   3.052 ± 0.129   ms/op
ClientPb.createUser                     sample  378702   2.532 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.933           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.695           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.065           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.500           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.269           ms/op
ClientPb.existUser                      sample  385564   2.488 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.935           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.564           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.412           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.993           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.943           ms/op
ClientPb.getUser                        sample  382339   2.509 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.972           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.863           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.677           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.500           ms/op
ClientPb.listUser                       sample  321887   2.980 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.698           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.916           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.521           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.679           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.221           ms/op
