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
# Warmup Iteration   1: 4.883 ops/ms
# Warmup Iteration   2: 12.088 ops/ms
# Warmup Iteration   3: 12.162 ops/ms
Iteration   1: 12.713 ops/ms
Iteration   2: 12.598 ops/ms
Iteration   3: 12.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.660 ±(99.9%) 1.059 ops/ms [Average]
  (min, avg, max) = (12.598, 12.660, 12.713), stdev = 0.058
  CI (99.9%): [11.601, 13.718] (assumes normal distribution)


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
# Warmup Iteration   1: 7.728 ops/ms
# Warmup Iteration   2: 12.712 ops/ms
# Warmup Iteration   3: 12.943 ops/ms
Iteration   1: 12.888 ops/ms
Iteration   2: 12.999 ops/ms
Iteration   3: 12.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.959 ±(99.9%) 1.133 ops/ms [Average]
  (min, avg, max) = (12.888, 12.959, 12.999), stdev = 0.062
  CI (99.9%): [11.826, 14.093] (assumes normal distribution)


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
# Warmup Iteration   1: 7.616 ops/ms
# Warmup Iteration   2: 12.241 ops/ms
# Warmup Iteration   3: 12.481 ops/ms
Iteration   1: 12.590 ops/ms
Iteration   2: 12.460 ops/ms
Iteration   3: 12.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.520 ±(99.9%) 1.200 ops/ms [Average]
  (min, avg, max) = (12.460, 12.520, 12.590), stdev = 0.066
  CI (99.9%): [11.320, 13.720] (assumes normal distribution)


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
# Warmup Iteration   1: 5.944 ops/ms
# Warmup Iteration   2: 10.294 ops/ms
# Warmup Iteration   3: 10.259 ops/ms
Iteration   1: 10.378 ops/ms
Iteration   2: 10.228 ops/ms
Iteration   3: 10.440 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.349 ±(99.9%) 1.991 ops/ms [Average]
  (min, avg, max) = (10.228, 10.349, 10.440), stdev = 0.109
  CI (99.9%): [8.358, 12.340] (assumes normal distribution)


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
# Warmup Iteration   1: 4.066 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.004 ms/op
Iteration   1: 2.597 ±(99.9%) 0.004 ms/op
Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
Iteration   3: 2.567 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.576 ±(99.9%) 0.333 ms/op [Average]
  (min, avg, max) = (2.564, 2.576, 2.597), stdev = 0.018
  CI (99.9%): [2.243, 2.908] (assumes normal distribution)


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.477 ±(99.9%) 0.004 ms/op
Iteration   1: 2.452 ±(99.9%) 0.005 ms/op
Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
Iteration   3: 2.459 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.456 ±(99.9%) 0.072 ms/op [Average]
  (min, avg, max) = (2.452, 2.456, 2.459), stdev = 0.004
  CI (99.9%): [2.385, 2.528] (assumes normal distribution)


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
# Warmup Iteration   1: 4.175 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.574 ±(99.9%) 0.005 ms/op
Iteration   1: 2.538 ±(99.9%) 0.005 ms/op
Iteration   2: 2.551 ±(99.9%) 0.004 ms/op
Iteration   3: 2.555 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.548 ±(99.9%) 0.156 ms/op [Average]
  (min, avg, max) = (2.538, 2.548, 2.555), stdev = 0.009
  CI (99.9%): [2.392, 2.704] (assumes normal distribution)


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
# Warmup Iteration   1: 4.858 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
Iteration   2: 3.039 ±(99.9%) 0.005 ms/op
Iteration   3: 3.024 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.034 ±(99.9%) 0.158 ms/op [Average]
  (min, avg, max) = (3.024, 3.034, 3.039), stdev = 0.009
  CI (99.9%): [2.876, 3.192] (assumes normal distribution)


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.694 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.533 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.932 ms/op
                 createUser·p0.999:  11.410 ms/op
                 createUser·p0.9999: 15.014 ms/op
                 createUser·p1.00:   15.237 ms/op

Iteration   2: 2.543 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.043 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   4.153 ms/op
                 createUser·p0.999:  9.983 ms/op
                 createUser·p0.9999: 13.746 ms/op
                 createUser·p1.00:   14.221 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   2.585 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  8.835 ms/op
                 createUser·p0.9999: 10.671 ms/op
                 createUser·p1.00:   10.863 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378666
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 181879 
    [ 2.500,  3.750) = 191769 
    [ 3.750,  5.000) = 3772 
    [ 5.000,  6.250) = 663 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 123 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 113 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      9.017 ms/op
     p(99.9900) =     13.798 ms/op
     p(99.9990) =     15.204 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   2.531 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.183 ms/op
                 existUser·p0.99:   3.809 ms/op
                 existUser·p0.999:  6.840 ms/op
                 existUser·p0.9999: 15.047 ms/op
                 existUser·p1.00:   15.958 ms/op

Iteration   2: 2.512 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.047 ms/op
                 existUser·p0.95:   3.162 ms/op
                 existUser·p0.99:   3.949 ms/op
                 existUser·p0.999:  9.875 ms/op
                 existUser·p0.9999: 15.012 ms/op
                 existUser·p1.00:   15.794 ms/op

Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   3.043 ms/op
                 existUser·p0.95:   3.174 ms/op
                 existUser·p0.99:   3.985 ms/op
                 existUser·p0.999:  6.521 ms/op
                 existUser·p0.9999: 12.249 ms/op
                 existUser·p1.00:   12.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 383175
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 42 
    [ 1.250,  2.500) = 187127 
    [ 2.500,  3.750) = 191302 
    [ 3.750,  5.000) = 3672 
    [ 5.000,  6.250) = 581 
    [ 6.250,  7.500) = 111 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 74 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.777 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.903 ms/op
     p(99.9000) =      6.747 ms/op
     p(99.9900) =     14.948 ms/op
     p(99.9990) =     15.764 ms/op
     p(99.9999) =     15.958 ms/op
    p(100.0000) =     15.958 ms/op


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.541 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.265 ms/op
                 getUser·p0.99:   4.125 ms/op
                 getUser·p0.999:  6.109 ms/op
                 getUser·p0.9999: 13.486 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   2: 2.525 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  9.771 ms/op
                 getUser·p0.9999: 14.719 ms/op
                 getUser·p1.00:   16.007 ms/op

Iteration   3: 2.533 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.527 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.273 ms/op
                 getUser·p0.99:   4.026 ms/op
                 getUser·p0.999:  8.700 ms/op
                 getUser·p0.9999: 11.835 ms/op
                 getUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378685
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 185722 
    [ 2.500,  3.750) = 187547 
    [ 3.750,  5.000) = 4277 
    [ 5.000,  6.250) = 650 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      7.156 ms/op
     p(99.9900) =     13.552 ms/op
     p(99.9990) =     15.773 ms/op
     p(99.9999) =     16.007 ms/op
    p(100.0000) =     16.007 ms/op


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
# Warmup Iteration   1: 4.831 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.009 ms/op
Iteration   1: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.773 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.825 ms/op
                 listUser·p0.999:  9.355 ms/op
                 listUser·p0.9999: 11.050 ms/op
                 listUser·p1.00:   12.075 ms/op

Iteration   2: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  10.011 ms/op
                 listUser·p0.9999: 12.839 ms/op
                 listUser·p1.00:   13.517 ms/op

Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  8.874 ms/op
                 listUser·p0.9999: 12.752 ms/op
                 listUser·p1.00:   13.124 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318829
  mean =      3.008 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 92185 
    [ 2.500,  3.750) = 187702 
    [ 3.750,  5.000) = 31739 
    [ 5.000,  6.250) = 5731 
    [ 6.250,  7.500) = 664 
    [ 7.500,  8.750) = 197 
    [ 8.750, 10.000) = 278 
    [10.000, 11.250) = 138 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.620 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     12.502 ms/op
     p(99.9990) =     13.409 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.660 ± 1.059  ops/ms
ClientPb.existUser                       thrpt       3  12.959 ± 1.133  ops/ms
ClientPb.getUser                         thrpt       3  12.520 ± 1.200  ops/ms
ClientPb.listUser                        thrpt       3  10.349 ± 1.991  ops/ms
ClientPb.createUser                       avgt       3   2.576 ± 0.333   ms/op
ClientPb.existUser                        avgt       3   2.456 ± 0.072   ms/op
ClientPb.getUser                          avgt       3   2.548 ± 0.156   ms/op
ClientPb.listUser                         avgt       3   3.034 ± 0.158   ms/op
ClientPb.createUser                     sample  378666   2.533 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.962           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.017           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.798           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.237           ms/op
ClientPb.existUser                      sample  383175   2.503 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.777           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.903           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.747           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.948           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.958           ms/op
ClientPb.getUser                        sample  378685   2.533 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.790           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.101           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.240           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.156           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.552           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.007           ms/op
ClientPb.listUser                       sample  318829   3.008 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.773           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.366           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.620           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.502           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.517           ms/op
