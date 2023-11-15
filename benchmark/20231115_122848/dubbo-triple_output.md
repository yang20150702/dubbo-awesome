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
# Warmup Iteration   1: 5.044 ops/ms
# Warmup Iteration   2: 12.005 ops/ms
# Warmup Iteration   3: 12.405 ops/ms
Iteration   1: 12.412 ops/ms
Iteration   2: 12.640 ops/ms
Iteration   3: 12.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.575 ±(99.9%) 2.602 ops/ms [Average]
  (min, avg, max) = (12.412, 12.575, 12.674), stdev = 0.143
  CI (99.9%): [9.974, 15.177] (assumes normal distribution)


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
# Warmup Iteration   1: 7.394 ops/ms
# Warmup Iteration   2: 12.808 ops/ms
# Warmup Iteration   3: 12.946 ops/ms
Iteration   1: 13.199 ops/ms
Iteration   2: 13.082 ops/ms
Iteration   3: 13.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.109 ±(99.9%) 1.457 ops/ms [Average]
  (min, avg, max) = (13.047, 13.109, 13.199), stdev = 0.080
  CI (99.9%): [11.653, 14.566] (assumes normal distribution)


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
# Warmup Iteration   1: 7.605 ops/ms
# Warmup Iteration   2: 12.426 ops/ms
# Warmup Iteration   3: 12.658 ops/ms
Iteration   1: 12.652 ops/ms
Iteration   2: 12.653 ops/ms
Iteration   3: 12.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.597 ±(99.9%) 1.737 ops/ms [Average]
  (min, avg, max) = (12.488, 12.597, 12.653), stdev = 0.095
  CI (99.9%): [10.861, 14.334] (assumes normal distribution)


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
# Warmup Iteration   1: 6.542 ops/ms
# Warmup Iteration   2: 10.464 ops/ms
# Warmup Iteration   3: 10.517 ops/ms
Iteration   1: 10.734 ops/ms
Iteration   2: 10.628 ops/ms
Iteration   3: 10.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.655 ±(99.9%) 1.271 ops/ms [Average]
  (min, avg, max) = (10.602, 10.655, 10.734), stdev = 0.070
  CI (99.9%): [9.383, 11.926] (assumes normal distribution)


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.566 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.494 ±(99.9%) 0.004 ms/op
Iteration   1: 2.507 ±(99.9%) 0.004 ms/op
Iteration   2: 2.535 ±(99.9%) 0.003 ms/op
Iteration   3: 2.527 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.523 ±(99.9%) 0.260 ms/op [Average]
  (min, avg, max) = (2.507, 2.523, 2.535), stdev = 0.014
  CI (99.9%): [2.263, 2.783] (assumes normal distribution)


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
# Warmup Iteration   1: 3.633 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.453 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.004 ms/op
Iteration   1: 2.434 ±(99.9%) 0.004 ms/op
Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
Iteration   3: 2.467 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.441 ±(99.9%) 0.417 ms/op [Average]
  (min, avg, max) = (2.423, 2.441, 2.467), stdev = 0.023
  CI (99.9%): [2.025, 2.858] (assumes normal distribution)


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
# Warmup Iteration   1: 3.976 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.489 ±(99.9%) 0.004 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
Iteration   2: 2.478 ±(99.9%) 0.005 ms/op
Iteration   3: 2.469 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.477 ±(99.9%) 0.140 ms/op [Average]
  (min, avg, max) = (2.469, 2.477, 2.484), stdev = 0.008
  CI (99.9%): [2.337, 2.617] (assumes normal distribution)


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
# Warmup Iteration   1: 4.544 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
Iteration   1: 3.010 ±(99.9%) 0.005 ms/op
Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
Iteration   3: 3.043 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.034 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (3.010, 3.034, 3.049), stdev = 0.021
  CI (99.9%): [2.651, 3.417] (assumes normal distribution)


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
# Warmup Iteration   1: 4.171 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.006 ms/op
Iteration   1: 2.521 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.993 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  11.653 ms/op
                 createUser·p0.9999: 15.668 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.846 ms/op
                 createUser·p0.999:  9.796 ms/op
                 createUser·p0.9999: 12.215 ms/op
                 createUser·p1.00:   13.173 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.539 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.067 ms/op
                 createUser·p0.999:  8.309 ms/op
                 createUser·p0.9999: 10.093 ms/op
                 createUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380851
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 183383 
    [ 2.500,  3.750) = 192219 
    [ 3.750,  5.000) = 3973 
    [ 5.000,  6.250) = 785 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 86 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      8.324 ms/op
     p(99.9900) =     14.759 ms/op
     p(99.9990) =     16.289 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.478 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.444 ±(99.9%) 0.005 ms/op
Iteration   1: 2.435 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  6.046 ms/op
                 existUser·p0.9999: 13.253 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   2: 2.439 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  5.784 ms/op
                 existUser·p0.9999: 12.430 ms/op
                 existUser·p1.00:   13.468 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.756 ms/op
                 existUser·p0.999:  6.618 ms/op
                 existUser·p0.9999: 14.760 ms/op
                 existUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392768
  mean =      2.442 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 29 
    [ 1.250,  2.500) = 193833 
    [ 2.500,  3.750) = 195313 
    [ 3.750,  5.000) = 2651 
    [ 5.000,  6.250) = 555 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.056 ms/op
     p(99.0000) =      3.674 ms/op
     p(99.9000) =      6.162 ms/op
     p(99.9900) =     13.405 ms/op
     p(99.9990) =     15.582 ms/op
     p(99.9999) =     15.745 ms/op
    p(100.0000) =     15.745 ms/op


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
# Warmup Iteration   1: 4.024 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.006 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.604 ms/op
                 getUser·p0.999:  11.479 ms/op
                 getUser·p0.9999: 14.945 ms/op
                 getUser·p1.00:   15.385 ms/op

Iteration   2: 2.505 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.021 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.047 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  9.756 ms/op
                 getUser·p0.9999: 16.191 ms/op
                 getUser·p1.00:   17.302 ms/op

Iteration   3: 2.519 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  8.718 ms/op
                 getUser·p0.9999: 10.746 ms/op
                 getUser·p1.00:   11.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 382643
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 190097 
    [ 2.500,  3.750) = 188003 
    [ 3.750,  5.000) = 3406 
    [ 5.000,  6.250) = 690 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 92 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.867 ms/op
     p(99.9000) =      8.722 ms/op
     p(99.9900) =     14.954 ms/op
     p(99.9990) =     16.728 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 4.733 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
Iteration   1: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.661 ms/op
                 listUser·p0.999:  9.038 ms/op
                 listUser·p0.9999: 11.688 ms/op
                 listUser·p1.00:   13.550 ms/op

Iteration   2: 3.005 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.633 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  9.011 ms/op
                 listUser·p0.9999: 12.759 ms/op
                 listUser·p1.00:   13.140 ms/op

Iteration   3: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.174 ms/op
                 listUser·p0.9999: 12.901 ms/op
                 listUser·p1.00:   13.631 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319239
  mean =      3.004 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 133 
    [ 1.250,  2.500) = 93874 
    [ 2.500,  3.750) = 186368 
    [ 3.750,  5.000) = 31349 
    [ 5.000,  6.250) = 6238 
    [ 6.250,  7.500) = 666 
    [ 7.500,  8.750) = 221 
    [ 8.750, 10.000) = 192 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.044 ms/op
     p(99.9900) =     12.541 ms/op
     p(99.9990) =     13.416 ms/op
     p(99.9999) =     13.631 ms/op
    p(100.0000) =     13.631 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.575 ± 2.602  ops/ms
ClientPb.existUser                       thrpt       3  13.109 ± 1.457  ops/ms
ClientPb.getUser                         thrpt       3  12.597 ± 1.737  ops/ms
ClientPb.listUser                        thrpt       3  10.655 ± 1.271  ops/ms
ClientPb.createUser                       avgt       3   2.523 ± 0.260   ms/op
ClientPb.existUser                        avgt       3   2.441 ± 0.417   ms/op
ClientPb.getUser                          avgt       3   2.477 ± 0.140   ms/op
ClientPb.listUser                         avgt       3   3.034 ± 0.383   ms/op
ClientPb.createUser                     sample  380851   2.519 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.539           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.576           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.324           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.759           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.417           ms/op
ClientPb.existUser                      sample  392768   2.442 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.844           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.674           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.162           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.405           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.745           ms/op
ClientPb.getUser                        sample  382643   2.507 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.769           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.867           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.722           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.954           ms/op
ClientPb.getUser:getUser·p1.00          sample          17.302           ms/op
ClientPb.listUser                       sample  319239   3.004 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.633           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.937           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.044           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.541           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.631           ms/op
