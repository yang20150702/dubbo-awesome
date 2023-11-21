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
# Warmup Iteration   1: 5.122 ops/ms
# Warmup Iteration   2: 12.087 ops/ms
# Warmup Iteration   3: 12.193 ops/ms
Iteration   1: 12.561 ops/ms
Iteration   2: 12.377 ops/ms
Iteration   3: 12.497 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.478 ±(99.9%) 1.709 ops/ms [Average]
  (min, avg, max) = (12.377, 12.478, 12.561), stdev = 0.094
  CI (99.9%): [10.769, 14.188] (assumes normal distribution)


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
# Warmup Iteration   1: 8.161 ops/ms
# Warmup Iteration   2: 12.976 ops/ms
# Warmup Iteration   3: 12.967 ops/ms
Iteration   1: 13.013 ops/ms
Iteration   2: 12.932 ops/ms
Iteration   3: 12.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.981 ±(99.9%) 0.782 ops/ms [Average]
  (min, avg, max) = (12.932, 12.981, 13.013), stdev = 0.043
  CI (99.9%): [12.199, 13.763] (assumes normal distribution)


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
# Warmup Iteration   1: 7.860 ops/ms
# Warmup Iteration   2: 12.459 ops/ms
# Warmup Iteration   3: 12.675 ops/ms
Iteration   1: 12.768 ops/ms
Iteration   2: 12.764 ops/ms
Iteration   3: 12.607 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.713 ±(99.9%) 1.678 ops/ms [Average]
  (min, avg, max) = (12.607, 12.713, 12.768), stdev = 0.092
  CI (99.9%): [11.035, 14.391] (assumes normal distribution)


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
# Warmup Iteration   1: 6.559 ops/ms
# Warmup Iteration   2: 10.244 ops/ms
# Warmup Iteration   3: 10.340 ops/ms
Iteration   1: 10.368 ops/ms
Iteration   2: 10.433 ops/ms
Iteration   3: 10.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.411 ±(99.9%) 0.676 ops/ms [Average]
  (min, avg, max) = (10.368, 10.411, 10.433), stdev = 0.037
  CI (99.9%): [9.735, 11.086] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.030 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.564 ±(99.9%) 0.003 ms/op
Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.535 ±(99.9%) 0.499 ms/op [Average]
  (min, avg, max) = (2.509, 2.535, 2.564), stdev = 0.027
  CI (99.9%): [2.036, 3.034] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.727 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.003 ms/op
Iteration   1: 2.454 ±(99.9%) 0.004 ms/op
Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.463 ±(99.9%) 0.231 ms/op [Average]
  (min, avg, max) = (2.454, 2.463, 2.477), stdev = 0.013
  CI (99.9%): [2.232, 2.694] (assumes normal distribution)


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.547 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.004 ms/op
Iteration   1: 2.542 ±(99.9%) 0.004 ms/op
Iteration   2: 2.526 ±(99.9%) 0.003 ms/op
Iteration   3: 2.565 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.544 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (2.526, 2.544, 2.565), stdev = 0.019
  CI (99.9%): [2.189, 2.899] (assumes normal distribution)


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
# Warmup Iteration   1: 4.714 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.060 ±(99.9%) 0.005 ms/op
Iteration   2: 3.065 ±(99.9%) 0.006 ms/op
Iteration   3: 3.045 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.057 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (3.045, 3.057, 3.065), stdev = 0.010
  CI (99.9%): [2.870, 3.243] (assumes normal distribution)


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
# Warmup Iteration   1: 4.281 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.540 ±(99.9%) 0.006 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.752 ms/op
                 createUser·p0.999:  11.978 ms/op
                 createUser·p0.9999: 13.566 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.850 ms/op
                 createUser·p0.999:  8.905 ms/op
                 createUser·p0.9999: 12.845 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.083 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.970 ms/op
                 createUser·p0.999:  8.203 ms/op
                 createUser·p0.9999: 11.529 ms/op
                 createUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381987
  mean =      2.511 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 183386 
    [ 2.500,  3.750) = 193851 
    [ 3.750,  5.000) = 3786 
    [ 5.000,  6.250) = 492 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 120 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      2.585 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.855 ms/op
     p(99.9000) =      8.242 ms/op
     p(99.9900) =     13.284 ms/op
     p(99.9990) =     13.853 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


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
# Warmup Iteration   1: 3.799 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.521 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
Iteration   1: 2.478 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.883 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.584 ms/op
                 existUser·p0.999:  7.351 ms/op
                 existUser·p0.9999: 21.175 ms/op
                 existUser·p1.00:   21.725 ms/op

Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  8.272 ms/op
                 existUser·p0.9999: 13.463 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   3: 2.492 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  8.749 ms/op
                 existUser·p0.9999: 15.505 ms/op
                 existUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386477
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 190847 
    [ 2.500,  5.000) = 194428 
    [ 5.000,  7.500) = 794 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 137 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.756 ms/op
     p(99.9000) =      8.741 ms/op
     p(99.9900) =     16.133 ms/op
     p(99.9990) =     21.402 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 3.851 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.541 ±(99.9%) 0.005 ms/op
Iteration   1: 2.551 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  12.688 ms/op
                 getUser·p0.9999: 14.344 ms/op
                 getUser·p1.00:   14.959 ms/op

Iteration   2: 2.591 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   2.626 ms/op
                 getUser·p0.90:   3.146 ms/op
                 getUser·p0.95:   3.387 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  6.352 ms/op
                 getUser·p0.9999: 12.173 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.690 ms/op
                 getUser·p0.999:  8.853 ms/op
                 getUser·p0.9999: 12.786 ms/op
                 getUser·p1.00:   13.582 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 375012
  mean =      2.558 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 180547 
    [ 2.500,  3.750) = 187107 
    [ 3.750,  5.000) = 5533 
    [ 5.000,  6.250) = 1324 
    [ 6.250,  7.500) = 73 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 60 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 122 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.256 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.061 ms/op
     p(99.9900) =     13.722 ms/op
     p(99.9990) =     14.881 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


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
# Warmup Iteration   1: 4.924 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.009 ms/op
Iteration   1: 3.092 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 10.382 ms/op
                 listUser·p1.00:   11.698 ms/op

Iteration   2: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.933 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.953 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 10.191 ms/op
                 listUser·p1.00:   10.846 ms/op

Iteration   3: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   2.998 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  8.880 ms/op
                 listUser·p0.9999: 11.248 ms/op
                 listUser·p1.00:   11.534 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 312554
  mean =      3.069 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 79639 
    [ 2.500,  3.750) = 189304 
    [ 3.750,  5.000) = 35908 
    [ 5.000,  6.250) = 6192 
    [ 6.250,  7.500) = 731 
    [ 7.500,  8.750) = 270 
    [ 8.750, 10.000) = 312 
    [10.000, 11.250) = 96 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.933 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     10.600 ms/op
     p(99.9990) =     11.524 ms/op
     p(99.9999) =     11.698 ms/op
    p(100.0000) =     11.698 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.478 ± 1.709  ops/ms
ClientPb.existUser                       thrpt       3  12.981 ± 0.782  ops/ms
ClientPb.getUser                         thrpt       3  12.713 ± 1.678  ops/ms
ClientPb.listUser                        thrpt       3  10.411 ± 0.676  ops/ms
ClientPb.createUser                       avgt       3   2.535 ± 0.499   ms/op
ClientPb.existUser                        avgt       3   2.463 ± 0.231   ms/op
ClientPb.getUser                          avgt       3   2.544 ± 0.355   ms/op
ClientPb.listUser                         avgt       3   3.057 ± 0.187   ms/op
ClientPb.createUser                     sample  381987   2.511 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.856           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.585           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.047           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.855           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.242           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.284           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.008           ms/op
ClientPb.existUser                      sample  386477   2.482 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.807           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.535           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.741           ms/op
ClientPb.existUser:existUser·p0.9999    sample          16.133           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.725           ms/op
ClientPb.getUser                        sample  375012   2.558 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.794           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.061           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.722           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.959           ms/op
ClientPb.listUser                       sample  312554   3.069 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.933           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.002           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.969           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.077           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.600           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.698           ms/op
