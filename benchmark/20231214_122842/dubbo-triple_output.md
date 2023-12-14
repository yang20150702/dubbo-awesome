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
# Warmup Iteration   1: 4.345 ops/ms
# Warmup Iteration   2: 11.914 ops/ms
# Warmup Iteration   3: 12.226 ops/ms
Iteration   1: 12.533 ops/ms
Iteration   2: 12.360 ops/ms
Iteration   3: 12.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.407 ±(99.9%) 2.017 ops/ms [Average]
  (min, avg, max) = (12.327, 12.407, 12.533), stdev = 0.111
  CI (99.9%): [10.389, 14.424] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 7.799 ops/ms
# Warmup Iteration   2: 12.864 ops/ms
# Warmup Iteration   3: 12.822 ops/ms
Iteration   1: 12.772 ops/ms
Iteration   2: 12.783 ops/ms
Iteration   3: 12.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.828 ±(99.9%) 1.607 ops/ms [Average]
  (min, avg, max) = (12.772, 12.828, 12.930), stdev = 0.088
  CI (99.9%): [11.221, 14.435] (assumes normal distribution)


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
# Warmup Iteration   1: 7.523 ops/ms
# Warmup Iteration   2: 12.506 ops/ms
# Warmup Iteration   3: 12.771 ops/ms
Iteration   1: 12.703 ops/ms
Iteration   2: 12.814 ops/ms
Iteration   3: 12.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.810 ±(99.9%) 1.912 ops/ms [Average]
  (min, avg, max) = (12.703, 12.810, 12.912), stdev = 0.105
  CI (99.9%): [10.898, 14.721] (assumes normal distribution)


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
# Warmup Iteration   1: 6.901 ops/ms
# Warmup Iteration   2: 10.422 ops/ms
# Warmup Iteration   3: 10.490 ops/ms
Iteration   1: 10.582 ops/ms
Iteration   2: 10.651 ops/ms
Iteration   3: 10.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.546 ±(99.9%) 2.300 ops/ms [Average]
  (min, avg, max) = (10.406, 10.546, 10.651), stdev = 0.126
  CI (99.9%): [8.246, 12.846] (assumes normal distribution)


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
# Warmup Iteration   1: 4.129 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.623 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.004 ms/op
Iteration   1: 2.538 ±(99.9%) 0.004 ms/op
Iteration   2: 2.602 ±(99.9%) 0.003 ms/op
Iteration   3: 2.551 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.564 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (2.538, 2.564, 2.602), stdev = 0.034
  CI (99.9%): [1.944, 3.184] (assumes normal distribution)


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
# Warmup Iteration   1: 3.807 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.457 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.496 ±(99.9%) 0.004 ms/op
Iteration   1: 2.470 ±(99.9%) 0.005 ms/op
Iteration   2: 2.479 ±(99.9%) 0.003 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.472 ±(99.9%) 0.111 ms/op [Average]
  (min, avg, max) = (2.468, 2.472, 2.479), stdev = 0.006
  CI (99.9%): [2.361, 2.584] (assumes normal distribution)


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.529 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.004 ms/op
Iteration   3: 2.473 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.476 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (2.464, 2.476, 2.491), stdev = 0.013
  CI (99.9%): [2.230, 2.722] (assumes normal distribution)


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
# Warmup Iteration   1: 4.853 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.006 ms/op
Iteration   1: 3.086 ±(99.9%) 0.006 ms/op
Iteration   2: 3.073 ±(99.9%) 0.006 ms/op
Iteration   3: 3.045 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.068 ±(99.9%) 0.378 ms/op [Average]
  (min, avg, max) = (3.045, 3.068, 3.086), stdev = 0.021
  CI (99.9%): [2.690, 3.446] (assumes normal distribution)


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.648 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.005 ms/op
Iteration   1: 2.541 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.541 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  11.034 ms/op
                 createUser·p0.9999: 13.491 ms/op
                 createUser·p1.00:   13.976 ms/op

Iteration   2: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.948 ms/op
                 createUser·p0.50:   2.626 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.588 ms/op
                 createUser·p0.999:  9.671 ms/op
                 createUser·p0.9999: 13.048 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.875 ms/op
                 createUser·p0.999:  9.283 ms/op
                 createUser·p0.9999: 15.489 ms/op
                 createUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377271
  mean =      2.542 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 180227 
    [ 2.500,  3.750) = 193069 
    [ 3.750,  5.000) = 2898 
    [ 5.000,  6.250) = 488 
    [ 6.250,  7.500) = 93 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      2.617 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.772 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     13.771 ms/op
     p(99.9990) =     15.793 ms/op
     p(99.9999) =     16.171 ms/op
    p(100.0000) =     16.171 ms/op


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.500 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.005 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.408 ms/op
                 existUser·p0.999:  6.241 ms/op
                 existUser·p0.9999: 14.433 ms/op
                 existUser·p1.00:   14.926 ms/op

Iteration   2: 2.457 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.650 ms/op
                 existUser·p0.999:  8.639 ms/op
                 existUser·p0.9999: 13.484 ms/op
                 existUser·p1.00:   14.156 ms/op

Iteration   3: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.502 ms/op
                 existUser·p0.999:  6.694 ms/op
                 existUser·p0.9999: 11.796 ms/op
                 existUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391242
  mean =      2.451 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 195063 
    [ 2.500,  3.750) = 193554 
    [ 3.750,  5.000) = 1872 
    [ 5.000,  6.250) = 268 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 70 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.518 ms/op
     p(99.9000) =      7.071 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     14.638 ms/op
     p(99.9999) =     14.926 ms/op
    p(100.0000) =     14.926 ms/op


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
# Warmup Iteration   1: 3.847 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
Iteration   1: 2.502 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  11.734 ms/op
                 getUser·p0.9999: 13.894 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   2: 2.514 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.817 ms/op
                 getUser·p0.999:  9.710 ms/op
                 getUser·p0.9999: 15.300 ms/op
                 getUser·p1.00:   15.630 ms/op

Iteration   3: 2.541 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  8.357 ms/op
                 getUser·p0.9999: 12.528 ms/op
                 getUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380771
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 67 
    [ 1.250,  2.500) = 188615 
    [ 2.500,  3.750) = 187031 
    [ 3.750,  5.000) = 3610 
    [ 5.000,  6.250) = 886 
    [ 6.250,  7.500) = 168 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 110 
    [12.500, 13.750) = 86 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.977 ms/op
     p(99.9000) =      8.373 ms/op
     p(99.9900) =     14.007 ms/op
     p(99.9990) =     15.545 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


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
# Warmup Iteration   1: 4.958 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.009 ms/op
Iteration   1: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  8.772 ms/op
                 listUser·p0.9999: 11.329 ms/op
                 listUser·p1.00:   11.813 ms/op

Iteration   2: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.554 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.839 ms/op
                 listUser·p0.9999: 11.436 ms/op
                 listUser·p1.00:   12.304 ms/op

Iteration   3: 3.045 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.830 ms/op
                 listUser·p0.9999: 10.928 ms/op
                 listUser·p1.00:   12.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316072
  mean =      3.035 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 87625 
    [ 2.500,  3.750) = 187943 
    [ 3.750,  5.000) = 33060 
    [ 5.000,  6.250) = 6066 
    [ 6.250,  7.500) = 589 
    [ 7.500,  8.750) = 192 
    [ 8.750, 10.000) = 283 
    [10.000, 11.250) = 162 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.469 ms/op
     p(99.9900) =     11.308 ms/op
     p(99.9990) =     12.242 ms/op
     p(99.9999) =     12.304 ms/op
    p(100.0000) =     12.304 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.407 ± 2.017  ops/ms
ClientPb.existUser                       thrpt       3  12.828 ± 1.607  ops/ms
ClientPb.getUser                         thrpt       3  12.810 ± 1.912  ops/ms
ClientPb.listUser                        thrpt       3  10.546 ± 2.300  ops/ms
ClientPb.createUser                       avgt       3   2.564 ± 0.620   ms/op
ClientPb.existUser                        avgt       3   2.472 ± 0.111   ms/op
ClientPb.getUser                          avgt       3   2.476 ± 0.246   ms/op
ClientPb.listUser                         avgt       3   3.068 ± 0.378   ms/op
ClientPb.createUser                     sample  377271   2.542 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.541           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.617           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.084           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.388           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.771           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.171           ms/op
ClientPb.existUser                      sample  391242   2.451 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.910           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.071           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.763           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.926           ms/op
ClientPb.getUser                        sample  380771   2.519 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.903           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.523           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.373           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.007           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.630           ms/op
ClientPb.listUser                       sample  316072   3.035 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.554           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.974           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.469           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.308           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.304           ms/op
