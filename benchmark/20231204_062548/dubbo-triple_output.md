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
# Warmup Iteration   1: 5.166 ops/ms
# Warmup Iteration   2: 12.026 ops/ms
# Warmup Iteration   3: 12.182 ops/ms
Iteration   1: 12.464 ops/ms
Iteration   2: 12.437 ops/ms
Iteration   3: 12.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.452 ±(99.9%) 0.247 ops/ms [Average]
  (min, avg, max) = (12.437, 12.452, 12.464), stdev = 0.014
  CI (99.9%): [12.205, 12.699] (assumes normal distribution)


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
# Warmup Iteration   1: 8.221 ops/ms
# Warmup Iteration   2: 12.932 ops/ms
# Warmup Iteration   3: 12.961 ops/ms
Iteration   1: 12.957 ops/ms
Iteration   2: 12.984 ops/ms
Iteration   3: 12.984 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.975 ±(99.9%) 0.283 ops/ms [Average]
  (min, avg, max) = (12.957, 12.975, 12.984), stdev = 0.015
  CI (99.9%): [12.692, 13.258] (assumes normal distribution)


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
# Warmup Iteration   1: 7.316 ops/ms
# Warmup Iteration   2: 12.333 ops/ms
# Warmup Iteration   3: 13.036 ops/ms
Iteration   1: 12.871 ops/ms
Iteration   2: 12.965 ops/ms
Iteration   3: 12.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.933 ±(99.9%) 0.982 ops/ms [Average]
  (min, avg, max) = (12.871, 12.933, 12.965), stdev = 0.054
  CI (99.9%): [11.951, 13.914] (assumes normal distribution)


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
# Warmup Iteration   1: 6.793 ops/ms
# Warmup Iteration   2: 10.707 ops/ms
# Warmup Iteration   3: 10.620 ops/ms
Iteration   1: 10.690 ops/ms
Iteration   2: 10.618 ops/ms
Iteration   3: 10.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.636 ±(99.9%) 0.872 ops/ms [Average]
  (min, avg, max) = (10.600, 10.636, 10.690), stdev = 0.048
  CI (99.9%): [9.764, 11.508] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.256 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.591 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.587 ±(99.9%) 0.004 ms/op
Iteration   1: 2.581 ±(99.9%) 0.005 ms/op
Iteration   2: 2.546 ±(99.9%) 0.003 ms/op
Iteration   3: 2.561 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.563 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (2.546, 2.563, 2.581), stdev = 0.018
  CI (99.9%): [2.235, 2.890] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.606 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.003 ms/op
Iteration   1: 2.484 ±(99.9%) 0.005 ms/op
Iteration   2: 2.453 ±(99.9%) 0.003 ms/op
Iteration   3: 2.475 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.471 ±(99.9%) 0.292 ms/op [Average]
  (min, avg, max) = (2.453, 2.471, 2.484), stdev = 0.016
  CI (99.9%): [2.179, 2.763] (assumes normal distribution)


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
# Warmup Iteration   1: 3.871 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.004 ms/op
Iteration   1: 2.507 ±(99.9%) 0.004 ms/op
Iteration   2: 2.541 ±(99.9%) 0.004 ms/op
Iteration   3: 2.538 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.529 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (2.507, 2.529, 2.541), stdev = 0.019
  CI (99.9%): [2.180, 2.877] (assumes normal distribution)


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
# Warmup Iteration   1: 4.742 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
Iteration   3: 3.032 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.028 ±(99.9%) 0.262 ms/op [Average]
  (min, avg, max) = (3.011, 3.028, 3.039), stdev = 0.014
  CI (99.9%): [2.766, 3.289] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.160 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.656 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.005 ms/op
Iteration   1: 2.521 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.828 ms/op
                 createUser·p0.999:  12.403 ms/op
                 createUser·p0.9999: 14.226 ms/op
                 createUser·p1.00:   14.680 ms/op

Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.868 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.936 ms/op
                 createUser·p0.999:  9.472 ms/op
                 createUser·p0.9999: 12.853 ms/op
                 createUser·p1.00:   13.828 ms/op

Iteration   3: 2.522 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.205 ms/op
                 createUser·p0.99:   4.129 ms/op
                 createUser·p0.999:  8.634 ms/op
                 createUser·p0.9999: 13.151 ms/op
                 createUser·p1.00:   13.369 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380488
  mean =      2.521 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 72 
    [ 1.250,  2.500) = 180875 
    [ 2.500,  3.750) = 194397 
    [ 3.750,  5.000) = 3827 
    [ 5.000,  6.250) = 777 
    [ 6.250,  7.500) = 96 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 82 
    [12.500, 13.750) = 127 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.957 ms/op
     p(99.9000) =      9.478 ms/op
     p(99.9900) =     13.369 ms/op
     p(99.9990) =     14.536 ms/op
     p(99.9999) =     14.680 ms/op
    p(100.0000) =     14.680 ms/op


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.488 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.470 ±(99.9%) 0.005 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.654 ms/op
                 existUser·p0.999:  6.637 ms/op
                 existUser·p0.9999: 14.045 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.894 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  7.551 ms/op
                 existUser·p0.9999: 13.074 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.191 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  6.486 ms/op
                 existUser·p0.9999: 10.535 ms/op
                 existUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387995
  mean =      2.472 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 54 
    [ 1.250,  2.500) = 189282 
    [ 2.500,  3.750) = 194326 
    [ 3.750,  5.000) = 3469 
    [ 5.000,  6.250) = 446 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.818 ms/op
     p(99.9000) =      6.734 ms/op
     p(99.9900) =     13.461 ms/op
     p(99.9990) =     14.502 ms/op
     p(99.9999) =     14.598 ms/op
    p(100.0000) =     14.598 ms/op


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
# Warmup Iteration   1: 3.897 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.539 ±(99.9%) 0.006 ms/op
Iteration   1: 2.520 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.916 ms/op
                 getUser·p0.999:  11.915 ms/op
                 getUser·p0.9999: 13.538 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   2: 2.519 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   4.076 ms/op
                 getUser·p0.999:  9.437 ms/op
                 getUser·p0.9999: 14.505 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.834 ms/op
                 getUser·p0.999:  7.979 ms/op
                 getUser·p0.9999: 11.600 ms/op
                 getUser·p1.00:   12.616 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380423
  mean =      2.522 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 187613 
    [ 2.500,  3.750) = 187758 
    [ 3.750,  5.000) = 3938 
    [ 5.000,  6.250) = 565 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 78 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     13.663 ms/op
     p(99.9990) =     14.618 ms/op
     p(99.9999) =     14.844 ms/op
    p(100.0000) =     14.844 ms/op


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
# Warmup Iteration   1: 4.725 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.009 ms/op
Iteration   1: 3.051 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 11.047 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   2: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.169 ms/op
                 listUser·p0.9999: 11.264 ms/op
                 listUser·p1.00:   11.780 ms/op

Iteration   3: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.009 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  9.994 ms/op
                 listUser·p0.9999: 12.640 ms/op
                 listUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315113
  mean =      3.044 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 87605 
    [ 2.500,  3.750) = 186000 
    [ 3.750,  5.000) = 33043 
    [ 5.000,  6.250) = 6884 
    [ 6.250,  7.500) = 785 
    [ 7.500,  8.750) = 224 
    [ 8.750, 10.000) = 261 
    [10.000, 11.250) = 144 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     11.944 ms/op
     p(99.9990) =     13.717 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.452 ± 0.247  ops/ms
ClientPb.existUser                       thrpt       3  12.975 ± 0.283  ops/ms
ClientPb.getUser                         thrpt       3  12.933 ± 0.982  ops/ms
ClientPb.listUser                        thrpt       3  10.636 ± 0.872  ops/ms
ClientPb.createUser                       avgt       3   2.563 ± 0.328   ms/op
ClientPb.existUser                        avgt       3   2.471 ± 0.292   ms/op
ClientPb.getUser                          avgt       3   2.529 ± 0.349   ms/op
ClientPb.listUser                         avgt       3   3.028 ± 0.262   ms/op
ClientPb.createUser                     sample  380488   2.521 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.868           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.478           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.369           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.680           ms/op
ClientPb.existUser                      sample  387995   2.472 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.766           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.818           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.734           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.461           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.598           ms/op
ClientPb.getUser                        sample  380423   2.522 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.959           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.733           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.663           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.844           ms/op
ClientPb.listUser                       sample  315113   3.044 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.802           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.726           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.503           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.944           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.844           ms/op
