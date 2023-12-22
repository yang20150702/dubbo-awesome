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
# Warmup Iteration   1: 5.273 ops/ms
# Warmup Iteration   2: 12.255 ops/ms
# Warmup Iteration   3: 12.390 ops/ms
Iteration   1: 12.645 ops/ms
Iteration   2: 12.780 ops/ms
Iteration   3: 12.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.714 ±(99.9%) 1.230 ops/ms [Average]
  (min, avg, max) = (12.645, 12.714, 12.780), stdev = 0.067
  CI (99.9%): [11.484, 13.944] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.928 ops/ms
# Warmup Iteration   2: 12.904 ops/ms
# Warmup Iteration   3: 13.143 ops/ms
Iteration   1: 13.115 ops/ms
Iteration   2: 13.216 ops/ms
Iteration   3: 13.059 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.130 ±(99.9%) 1.453 ops/ms [Average]
  (min, avg, max) = (13.059, 13.130, 13.216), stdev = 0.080
  CI (99.9%): [11.677, 14.583] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.128 ops/ms
# Warmup Iteration   2: 12.546 ops/ms
# Warmup Iteration   3: 12.601 ops/ms
Iteration   1: 12.646 ops/ms
Iteration   2: 12.531 ops/ms
Iteration   3: 12.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.643 ±(99.9%) 2.019 ops/ms [Average]
  (min, avg, max) = (12.531, 12.643, 12.753), stdev = 0.111
  CI (99.9%): [10.624, 14.663] (assumes normal distribution)


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
# Warmup Iteration   1: 6.907 ops/ms
# Warmup Iteration   2: 10.570 ops/ms
# Warmup Iteration   3: 10.716 ops/ms
Iteration   1: 10.753 ops/ms
Iteration   2: 10.836 ops/ms
Iteration   3: 10.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.775 ±(99.9%) 0.974 ops/ms [Average]
  (min, avg, max) = (10.737, 10.775, 10.836), stdev = 0.053
  CI (99.9%): [9.801, 11.750] (assumes normal distribution)


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.585 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.004 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.003 ms/op
Iteration   3: 2.543 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.509 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (2.477, 2.509, 2.543), stdev = 0.033
  CI (99.9%): [1.905, 3.114] (assumes normal distribution)


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
# Warmup Iteration   1: 3.558 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.427 ±(99.9%) 0.004 ms/op
Iteration   1: 2.422 ±(99.9%) 0.004 ms/op
Iteration   2: 2.419 ±(99.9%) 0.004 ms/op
Iteration   3: 2.446 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.429 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (2.419, 2.429, 2.446), stdev = 0.015
  CI (99.9%): [2.161, 2.697] (assumes normal distribution)


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
# Warmup Iteration   1: 3.803 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.539 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.004 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
Iteration   3: 2.462 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.470 ±(99.9%) 0.134 ms/op [Average]
  (min, avg, max) = (2.462, 2.470, 2.475), stdev = 0.007
  CI (99.9%): [2.336, 2.604] (assumes normal distribution)


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
# Warmup Iteration   1: 4.838 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.005 ms/op
Iteration   1: 2.991 ±(99.9%) 0.005 ms/op
Iteration   2: 2.982 ±(99.9%) 0.005 ms/op
Iteration   3: 2.985 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.986 ±(99.9%) 0.081 ms/op [Average]
  (min, avg, max) = (2.982, 2.986, 2.991), stdev = 0.004
  CI (99.9%): [2.905, 3.067] (assumes normal distribution)


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.553 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
Iteration   1: 2.461 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   2.970 ms/op
                 createUser·p0.95:   3.068 ms/op
                 createUser·p0.99:   3.572 ms/op
                 createUser·p0.999:  7.198 ms/op
                 createUser·p0.9999: 13.288 ms/op
                 createUser·p1.00:   14.090 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.072 ms/op
                 createUser·p0.99:   3.437 ms/op
                 createUser·p0.999:  6.785 ms/op
                 createUser·p0.9999: 17.719 ms/op
                 createUser·p1.00:   18.285 ms/op

Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.623 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.895 ms/op
                 createUser·p0.999:  8.700 ms/op
                 createUser·p0.9999: 11.787 ms/op
                 createUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387253
  mean =      2.477 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 186446 
    [ 2.500,  3.750) = 197551 
    [ 3.750,  5.000) = 2421 
    [ 5.000,  6.250) = 325 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 68 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 114 
    [12.500, 13.750) = 80 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.092 ms/op
     p(99.0000) =      3.654 ms/op
     p(99.9000) =      8.679 ms/op
     p(99.9900) =     13.584 ms/op
     p(99.9990) =     18.219 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 3.731 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.485 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.798 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  5.727 ms/op
                 existUser·p0.9999: 13.959 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   2: 2.445 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.457 ms/op
                 existUser·p0.999:  5.943 ms/op
                 existUser·p0.9999: 15.284 ms/op
                 existUser·p1.00:   15.761 ms/op

Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.166 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  9.245 ms/op
                 existUser·p0.9999: 12.063 ms/op
                 existUser·p1.00:   12.550 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389412
  mean =      2.463 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 192465 
    [ 2.500,  3.750) = 193986 
    [ 3.750,  5.000) = 2147 
    [ 5.000,  6.250) = 288 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 105 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =      8.012 ms/op
     p(99.9900) =     14.026 ms/op
     p(99.9990) =     15.699 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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
# Warmup Iteration   1: 3.780 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.006 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.516 ms/op
                 getUser·p0.999:  8.877 ms/op
                 getUser·p0.9999: 14.283 ms/op
                 getUser·p1.00:   14.647 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.142 ms/op
                 getUser·p0.99:   3.568 ms/op
                 getUser·p0.999:  8.053 ms/op
                 getUser·p0.9999: 11.921 ms/op
                 getUser·p1.00:   12.763 ms/op

Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.908 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  8.483 ms/op
                 getUser·p0.9999: 10.461 ms/op
                 getUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383165
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 43 
    [ 1.250,  2.500) = 189663 
    [ 2.500,  3.750) = 189349 
    [ 3.750,  5.000) = 3265 
    [ 5.000,  6.250) = 411 
    [ 6.250,  7.500) = 47 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 122 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.801 ms/op
     p(99.9000) =      8.468 ms/op
     p(99.9900) =     13.184 ms/op
     p(99.9990) =     14.511 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 4.509 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
Iteration   1: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.807 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.725 ms/op
                 listUser·p0.999:  8.673 ms/op
                 listUser·p0.9999: 11.232 ms/op
                 listUser·p1.00:   12.403 ms/op

Iteration   2: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.671 ms/op
                 listUser·p0.999:  9.364 ms/op
                 listUser·p0.9999: 11.225 ms/op
                 listUser·p1.00:   11.436 ms/op

Iteration   3: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  10.205 ms/op
                 listUser·p0.9999: 13.074 ms/op
                 listUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 314417
  mean =      3.051 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 110 
    [ 1.250,  2.500) = 85654 
    [ 2.500,  3.750) = 186997 
    [ 3.750,  5.000) = 33714 
    [ 5.000,  6.250) = 6354 
    [ 6.250,  7.500) = 851 
    [ 7.500,  8.750) = 281 
    [ 8.750, 10.000) = 208 
    [10.000, 11.250) = 171 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.561 ms/op
     p(99.9900) =     12.658 ms/op
     p(99.9990) =     13.973 ms/op
     p(99.9999) =     14.189 ms/op
    p(100.0000) =     14.189 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.714 ± 1.230  ops/ms
ClientPb.existUser                       thrpt       3  13.130 ± 1.453  ops/ms
ClientPb.getUser                         thrpt       3  12.643 ± 2.019  ops/ms
ClientPb.listUser                        thrpt       3  10.775 ± 0.974  ops/ms
ClientPb.createUser                       avgt       3   2.509 ± 0.604   ms/op
ClientPb.existUser                        avgt       3   2.429 ± 0.268   ms/op
ClientPb.getUser                          avgt       3   2.470 ± 0.134   ms/op
ClientPb.listUser                         avgt       3   2.986 ± 0.081   ms/op
ClientPb.createUser                     sample  387253   2.477 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.623           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           2.994           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.654           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.679           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.584           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.285           ms/op
ClientPb.existUser                      sample  389412   2.463 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.798           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.523           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.012           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.026           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.761           ms/op
ClientPb.getUser                        sample  383165   2.503 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.908           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.468           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.184           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.647           ms/op
ClientPb.listUser                       sample  314417   3.051 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.807           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.986           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.448           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.677           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.561           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.658           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.189           ms/op
