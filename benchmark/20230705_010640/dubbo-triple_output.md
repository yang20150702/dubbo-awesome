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
# Warmup Iteration   2: 5.479 ops/ms
# Warmup Iteration   3: 8.239 ops/ms
Iteration   1: 9.445 ops/ms
Iteration   2: 9.321 ops/ms
Iteration   3: 9.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.310 ±(99.9%) 2.548 ops/ms [Average]
  (min, avg, max) = (9.166, 9.310, 9.445), stdev = 0.140
  CI (99.9%): [6.762, 11.859] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.133 ops/ms
# Warmup Iteration   2: 8.793 ops/ms
# Warmup Iteration   3: 9.239 ops/ms
Iteration   1: 9.799 ops/ms
Iteration   2: 9.810 ops/ms
Iteration   3: 9.881 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.830 ±(99.9%) 0.808 ops/ms [Average]
  (min, avg, max) = (9.799, 9.830, 9.881), stdev = 0.044
  CI (99.9%): [9.022, 10.638] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.182 ops/ms
# Warmup Iteration   2: 7.809 ops/ms
# Warmup Iteration   3: 9.153 ops/ms
Iteration   1: 9.530 ops/ms
Iteration   2: 9.621 ops/ms
Iteration   3: 8.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.371 ±(99.9%) 6.506 ops/ms [Average]
  (min, avg, max) = (8.963, 9.371, 9.621), stdev = 0.357
  CI (99.9%): [2.866, 15.877] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.701 ops/ms
# Warmup Iteration   2: 7.199 ops/ms
# Warmup Iteration   3: 7.920 ops/ms
Iteration   1: 7.962 ops/ms
Iteration   2: 8.071 ops/ms
Iteration   3: 8.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.072 ±(99.9%) 2.013 ops/ms [Average]
  (min, avg, max) = (7.962, 8.072, 8.183), stdev = 0.110
  CI (99.9%): [6.059, 10.085] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 10.962 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.005 ms/op
Iteration   1: 3.344 ±(99.9%) 0.006 ms/op
Iteration   2: 3.420 ±(99.9%) 0.005 ms/op
Iteration   3: 3.404 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.389 ±(99.9%) 0.727 ms/op [Average]
  (min, avg, max) = (3.344, 3.389, 3.420), stdev = 0.040
  CI (99.9%): [2.662, 4.117] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.525 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.512 ±(99.9%) 0.006 ms/op
Iteration   1: 3.388 ±(99.9%) 0.008 ms/op
Iteration   2: 3.231 ±(99.9%) 0.008 ms/op
Iteration   3: 3.348 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.322 ±(99.9%) 1.494 ms/op [Average]
  (min, avg, max) = (3.231, 3.322, 3.388), stdev = 0.082
  CI (99.9%): [1.829, 4.816] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.929 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.698 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.004 ms/op
Iteration   1: 3.452 ±(99.9%) 0.009 ms/op
Iteration   2: 3.369 ±(99.9%) 0.003 ms/op
Iteration   3: 3.418 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.413 ±(99.9%) 0.756 ms/op [Average]
  (min, avg, max) = (3.369, 3.413, 3.452), stdev = 0.041
  CI (99.9%): [2.657, 4.169] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.517 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.008 ms/op
Iteration   1: 4.033 ±(99.9%) 0.009 ms/op
Iteration   2: 3.891 ±(99.9%) 0.012 ms/op
Iteration   3: 3.821 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.915 ±(99.9%) 1.969 ms/op [Average]
  (min, avg, max) = (3.821, 3.915, 4.033), stdev = 0.108
  CI (99.9%): [1.945, 5.884] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.761 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.011 ms/op
Iteration   1: 3.488 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.035 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  20.638 ms/op
                 createUser·p0.9999: 25.395 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   2: 3.318 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  18.153 ms/op
                 createUser·p0.9999: 25.845 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   3: 3.476 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.425 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.977 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   6.971 ms/op
                 createUser·p0.999:  21.135 ms/op
                 createUser·p0.9999: 28.535 ms/op
                 createUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279944
  mean =      3.425 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10219 
    [ 2.500,  5.000) = 261698 
    [ 5.000,  7.500) = 6687 
    [ 7.500, 10.000) = 904 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 84 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      6.521 ms/op
     p(99.9000) =     20.813 ms/op
     p(99.9900) =     26.149 ms/op
     p(99.9990) =     29.826 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.696 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.678 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.392 ±(99.9%) 0.009 ms/op
Iteration   1: 3.344 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.262 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  18.892 ms/op
                 existUser·p0.9999: 22.938 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   2: 3.255 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.243 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  13.837 ms/op
                 existUser·p0.9999: 25.340 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   3: 3.569 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   6.724 ms/op
                 existUser·p0.999:  14.284 ms/op
                 existUser·p0.9999: 26.052 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283662
  mean =      3.384 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9044 
    [ 2.500,  5.000) = 268177 
    [ 5.000,  7.500) = 5252 
    [ 7.500, 10.000) = 557 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.833 ms/op
     p(99.9000) =     14.194 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     26.601 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.390 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.011 ms/op
Iteration   1: 3.445 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.556 ms/op
                 getUser·p0.50:   3.355 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.219 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  12.506 ms/op
                 getUser·p0.9999: 26.608 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   2: 3.416 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.022 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  21.146 ms/op
                 getUser·p0.9999: 24.510 ms/op
                 getUser·p1.00:   26.214 ms/op

Iteration   3: 3.362 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  19.856 ms/op
                 getUser·p0.9999: 26.755 ms/op
                 getUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 281560
  mean =      3.407 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9690 
    [ 2.500,  5.000) = 265954 
    [ 5.000,  7.500) = 5101 
    [ 7.500, 10.000) = 469 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     13.114 ms/op
     p(99.9900) =     26.083 ms/op
     p(99.9990) =     27.514 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.320 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.441 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.019 ±(99.9%) 0.012 ms/op
Iteration   1: 4.217 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   4.018 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  19.500 ms/op
                 listUser·p0.9999: 24.492 ms/op
                 listUser·p1.00:   26.837 ms/op

Iteration   2: 3.986 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.486 ms/op
                 listUser·p0.999:  16.022 ms/op
                 listUser·p0.9999: 21.823 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   3: 4.109 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   7.700 ms/op
                 listUser·p0.999:  14.700 ms/op
                 listUser·p0.9999: 18.903 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233821
  mean =      4.102 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 222354 
    [ 5.000,  7.500) = 8600 
    [ 7.500, 10.000) = 1935 
    [10.000, 12.500) = 423 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 73 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.608 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     16.171 ms/op
     p(99.9900) =     22.986 ms/op
     p(99.9990) =     24.882 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.310 ± 2.548  ops/ms
ClientPb.existUser                       thrpt       3   9.830 ± 0.808  ops/ms
ClientPb.getUser                         thrpt       3   9.371 ± 6.506  ops/ms
ClientPb.listUser                        thrpt       3   8.072 ± 2.013  ops/ms
ClientPb.createUser                       avgt       3   3.389 ± 0.727   ms/op
ClientPb.existUser                        avgt       3   3.322 ± 1.494   ms/op
ClientPb.getUser                          avgt       3   3.413 ± 0.756   ms/op
ClientPb.listUser                         avgt       3   3.915 ± 1.969   ms/op
ClientPb.createUser                     sample  279944   3.425 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.884           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.301           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.813           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.149           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.343           ms/op
ClientPb.existUser                      sample  283662   3.384 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.083           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.305           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.833           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.194           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.068           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.903           ms/op
ClientPb.getUser                        sample  281560   3.407 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.022           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.964           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.114           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.083           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.229           ms/op
ClientPb.listUser                       sample  233821   4.102 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.608           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.981           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.832           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.171           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.986           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.837           ms/op
