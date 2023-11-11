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
# Warmup Iteration   1: 4.756 ops/ms
# Warmup Iteration   2: 11.932 ops/ms
# Warmup Iteration   3: 12.288 ops/ms
Iteration   1: 12.579 ops/ms
Iteration   2: 12.391 ops/ms
Iteration   3: 12.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.553 ±(99.9%) 2.746 ops/ms [Average]
  (min, avg, max) = (12.391, 12.553, 12.689), stdev = 0.151
  CI (99.9%): [9.807, 15.299] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.876 ops/ms
# Warmup Iteration   2: 12.751 ops/ms
# Warmup Iteration   3: 12.844 ops/ms
Iteration   1: 12.816 ops/ms
Iteration   2: 12.836 ops/ms
Iteration   3: 12.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.829 ±(99.9%) 0.208 ops/ms [Average]
  (min, avg, max) = (12.816, 12.829, 12.836), stdev = 0.011
  CI (99.9%): [12.621, 13.037] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.178 ops/ms
# Warmup Iteration   2: 12.389 ops/ms
# Warmup Iteration   3: 12.713 ops/ms
Iteration   1: 12.651 ops/ms
Iteration   2: 12.774 ops/ms
Iteration   3: 12.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.709 ±(99.9%) 1.129 ops/ms [Average]
  (min, avg, max) = (12.651, 12.709, 12.774), stdev = 0.062
  CI (99.9%): [11.580, 13.838] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.782 ops/ms
# Warmup Iteration   2: 10.391 ops/ms
# Warmup Iteration   3: 10.541 ops/ms
Iteration   1: 10.494 ops/ms
Iteration   2: 10.535 ops/ms
Iteration   3: 10.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.499 ±(99.9%) 0.617 ops/ms [Average]
  (min, avg, max) = (10.468, 10.499, 10.535), stdev = 0.034
  CI (99.9%): [9.882, 11.116] (assumes normal distribution)


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.618 ±(99.9%) 0.005 ms/op
Iteration   1: 2.553 ±(99.9%) 0.003 ms/op
Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
Iteration   3: 2.578 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.553 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (2.528, 2.553, 2.578), stdev = 0.025
  CI (99.9%): [2.099, 3.008] (assumes normal distribution)


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
# Warmup Iteration   1: 3.869 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.003 ms/op
Iteration   1: 2.464 ±(99.9%) 0.003 ms/op
Iteration   2: 2.473 ±(99.9%) 0.004 ms/op
Iteration   3: 2.460 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.466 ±(99.9%) 0.125 ms/op [Average]
  (min, avg, max) = (2.460, 2.466, 2.473), stdev = 0.007
  CI (99.9%): [2.341, 2.591] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.023 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.618 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.004 ms/op
Iteration   1: 2.499 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.524 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.511 ±(99.9%) 0.231 ms/op [Average]
  (min, avg, max) = (2.499, 2.511, 2.524), stdev = 0.013
  CI (99.9%): [2.280, 2.742] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.614 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.005 ms/op
Iteration   1: 3.039 ±(99.9%) 0.005 ms/op
Iteration   2: 3.023 ±(99.9%) 0.005 ms/op
Iteration   3: 3.027 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.030 ±(99.9%) 0.150 ms/op [Average]
  (min, avg, max) = (3.023, 3.030, 3.039), stdev = 0.008
  CI (99.9%): [2.880, 3.180] (assumes normal distribution)


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
# Warmup Iteration   1: 4.189 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.687 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.533 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.998 ms/op
                 createUser·p0.999:  11.315 ms/op
                 createUser·p0.9999: 13.548 ms/op
                 createUser·p1.00:   14.516 ms/op

Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.928 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.801 ms/op
                 createUser·p0.999:  9.742 ms/op
                 createUser·p0.9999: 11.488 ms/op
                 createUser·p1.00:   12.222 ms/op

Iteration   3: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  8.072 ms/op
                 createUser·p0.9999: 9.959 ms/op
                 createUser·p1.00:   10.355 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378481
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 180660 
    [ 2.500,  3.750) = 193356 
    [ 3.750,  5.000) = 3520 
    [ 5.000,  6.250) = 451 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 114 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 116 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      2.605 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      8.106 ms/op
     p(99.9900) =     12.864 ms/op
     p(99.9990) =     14.197 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 3.780 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.536 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  11.154 ms/op
                 existUser·p0.9999: 13.533 ms/op
                 existUser·p1.00:   13.713 ms/op

Iteration   2: 2.503 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   3.056 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  5.898 ms/op
                 existUser·p0.9999: 12.161 ms/op
                 existUser·p1.00:   12.386 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.789 ms/op
                 existUser·p0.999:  8.637 ms/op
                 existUser·p0.9999: 11.322 ms/op
                 existUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383318
  mean =      2.502 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 46 
    [ 1.250,  2.500) = 188801 
    [ 2.500,  3.750) = 190805 
    [ 3.750,  5.000) = 2875 
    [ 5.000,  6.250) = 394 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.889 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      6.469 ms/op
     p(99.9900) =     13.249 ms/op
     p(99.9990) =     13.618 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.006 ms/op
Iteration   1: 2.529 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  12.398 ms/op
                 getUser·p0.9999: 13.943 ms/op
                 getUser·p1.00:   14.631 ms/op

Iteration   2: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  8.123 ms/op
                 getUser·p0.9999: 13.278 ms/op
                 getUser·p1.00:   14.189 ms/op

Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.844 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  8.802 ms/op
                 getUser·p0.9999: 11.440 ms/op
                 getUser·p1.00:   11.649 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381483
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 186701 
    [ 2.500,  3.750) = 188171 
    [ 3.750,  5.000) = 5094 
    [ 5.000,  6.250) = 961 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 127 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 138 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      8.807 ms/op
     p(99.9900) =     13.582 ms/op
     p(99.9990) =     14.095 ms/op
     p(99.9999) =     14.631 ms/op
    p(100.0000) =     14.631 ms/op


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
# Warmup Iteration   1: 4.822 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.009 ms/op
Iteration   1: 3.058 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.007 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.973 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  8.651 ms/op
                 listUser·p0.9999: 10.094 ms/op
                 listUser·p1.00:   10.568 ms/op

Iteration   2: 3.065 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.763 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   5.906 ms/op
                 listUser·p0.999:  10.109 ms/op
                 listUser·p0.9999: 11.474 ms/op
                 listUser·p1.00:   12.157 ms/op

Iteration   3: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.191 ms/op
                 listUser·p0.9999: 12.195 ms/op
                 listUser·p1.00:   12.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314179
  mean =      3.053 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 87150 
    [ 2.500,  3.750) = 185639 
    [ 3.750,  5.000) = 32925 
    [ 5.000,  6.250) = 6780 
    [ 6.250,  7.500) = 932 
    [ 7.500,  8.750) = 225 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     11.265 ms/op
     p(99.9990) =     12.876 ms/op
     p(99.9999) =     12.911 ms/op
    p(100.0000) =     12.911 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.553 ± 2.746  ops/ms
ClientPb.existUser                       thrpt       3  12.829 ± 0.208  ops/ms
ClientPb.getUser                         thrpt       3  12.709 ± 1.129  ops/ms
ClientPb.listUser                        thrpt       3  10.499 ± 0.617  ops/ms
ClientPb.createUser                       avgt       3   2.553 ± 0.454   ms/op
ClientPb.existUser                        avgt       3   2.466 ± 0.125   ms/op
ClientPb.getUser                          avgt       3   2.511 ± 0.231   ms/op
ClientPb.listUser                         avgt       3   3.030 ± 0.150   ms/op
ClientPb.createUser                     sample  378481   2.534 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.928           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.605           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.106           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.864           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.516           ms/op
ClientPb.existUser                      sample  383318   2.502 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.889           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.469           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.249           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.713           ms/op
ClientPb.getUser                        sample  381483   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.844           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.052           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.182           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.807           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.582           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.631           ms/op
ClientPb.listUser                       sample  314179   3.053 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.763           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.994           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.743           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.355           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.265           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.911           ms/op
