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
# Warmup Iteration   1: 4.539 ops/ms
# Warmup Iteration   2: 11.550 ops/ms
# Warmup Iteration   3: 12.100 ops/ms
Iteration   1: 12.262 ops/ms
Iteration   2: 12.309 ops/ms
Iteration   3: 12.457 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.343 ±(99.9%) 1.850 ops/ms [Average]
  (min, avg, max) = (12.262, 12.343, 12.457), stdev = 0.101
  CI (99.9%): [10.493, 14.193] (assumes normal distribution)


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
# Warmup Iteration   1: 7.631 ops/ms
# Warmup Iteration   2: 12.812 ops/ms
# Warmup Iteration   3: 13.051 ops/ms
Iteration   1: 12.951 ops/ms
Iteration   2: 12.990 ops/ms
Iteration   3: 12.886 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.942 ±(99.9%) 0.959 ops/ms [Average]
  (min, avg, max) = (12.886, 12.942, 12.990), stdev = 0.053
  CI (99.9%): [11.983, 13.901] (assumes normal distribution)


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
# Warmup Iteration   1: 7.493 ops/ms
# Warmup Iteration   2: 12.711 ops/ms
# Warmup Iteration   3: 12.701 ops/ms
Iteration   1: 12.737 ops/ms
Iteration   2: 12.743 ops/ms
Iteration   3: 12.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.757 ±(99.9%) 0.552 ops/ms [Average]
  (min, avg, max) = (12.737, 12.757, 12.792), stdev = 0.030
  CI (99.9%): [12.206, 13.309] (assumes normal distribution)


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
# Warmup Iteration   1: 6.699 ops/ms
# Warmup Iteration   2: 10.301 ops/ms
# Warmup Iteration   3: 10.419 ops/ms
Iteration   1: 10.374 ops/ms
Iteration   2: 10.558 ops/ms
Iteration   3: 10.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.474 ±(99.9%) 1.699 ops/ms [Average]
  (min, avg, max) = (10.374, 10.474, 10.558), stdev = 0.093
  CI (99.9%): [8.774, 12.173] (assumes normal distribution)


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.622 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.004 ms/op
Iteration   1: 2.512 ±(99.9%) 0.004 ms/op
Iteration   2: 2.544 ±(99.9%) 0.004 ms/op
Iteration   3: 2.591 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.549 ±(99.9%) 0.727 ms/op [Average]
  (min, avg, max) = (2.512, 2.549, 2.591), stdev = 0.040
  CI (99.9%): [1.822, 3.276] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.827 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
Iteration   3: 2.515 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.499 ±(99.9%) 0.359 ms/op [Average]
  (min, avg, max) = (2.477, 2.499, 2.515), stdev = 0.020
  CI (99.9%): [2.140, 2.858] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.064 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.004 ms/op
Iteration   1: 2.542 ±(99.9%) 0.005 ms/op
Iteration   2: 2.518 ±(99.9%) 0.004 ms/op
Iteration   3: 2.492 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.517 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (2.492, 2.517, 2.542), stdev = 0.025
  CI (99.9%): [2.063, 2.971] (assumes normal distribution)


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
# Warmup Iteration   1: 4.795 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.006 ms/op
Iteration   1: 3.033 ±(99.9%) 0.003 ms/op
Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
Iteration   3: 3.037 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (3.033, 3.036, 3.039), stdev = 0.003
  CI (99.9%): [2.988, 3.085] (assumes normal distribution)


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.527 ±(99.9%) 0.006 ms/op
Iteration   1: 2.552 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.293 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  11.567 ms/op
                 createUser·p0.9999: 14.238 ms/op
                 createUser·p1.00:   16.007 ms/op

Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.052 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.760 ms/op
                 createUser·p0.999:  9.559 ms/op
                 createUser·p0.9999: 13.672 ms/op
                 createUser·p1.00:   15.483 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.879 ms/op
                 createUser·p0.999:  9.765 ms/op
                 createUser·p0.9999: 11.770 ms/op
                 createUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379456
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 63 
    [ 1.250,  2.500) = 180682 
    [ 2.500,  3.750) = 193037 
    [ 3.750,  5.000) = 4537 
    [ 5.000,  6.250) = 610 
    [ 6.250,  7.500) = 120 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 107 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      4.014 ms/op
     p(99.9000) =      9.684 ms/op
     p(99.9900) =     13.813 ms/op
     p(99.9990) =     15.369 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.913 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
Iteration   1: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.170 ms/op
                 existUser·p0.99:   4.035 ms/op
                 existUser·p0.999:  5.829 ms/op
                 existUser·p0.9999: 13.992 ms/op
                 existUser·p1.00:   14.975 ms/op

Iteration   2: 2.479 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.841 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.854 ms/op
                 existUser·p0.999:  9.552 ms/op
                 existUser·p0.9999: 16.871 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.905 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.138 ms/op
                 existUser·p0.99:   3.817 ms/op
                 existUser·p0.999:  8.995 ms/op
                 existUser·p0.9999: 11.452 ms/op
                 existUser·p1.00:   12.222 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387005
  mean =      2.478 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 192760 
    [ 2.500,  3.750) = 189372 
    [ 3.750,  5.000) = 3880 
    [ 5.000,  6.250) = 502 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 110 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.908 ms/op
     p(99.9000) =      7.078 ms/op
     p(99.9900) =     14.079 ms/op
     p(99.9990) =     17.380 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 4.004 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.591 ±(99.9%) 0.007 ms/op
Iteration   1: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.195 ms/op
                 getUser·p0.99:   3.805 ms/op
                 getUser·p0.999:  11.732 ms/op
                 getUser·p0.9999: 14.379 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   2: 2.517 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.033 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.035 ms/op
                 getUser·p0.999:  9.470 ms/op
                 getUser·p0.9999: 22.761 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.047 ms/op
                 getUser·p0.999:  8.990 ms/op
                 getUser·p0.9999: 13.621 ms/op
                 getUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381454
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 187503 
    [ 2.500,  5.000) = 193035 
    [ 5.000,  7.500) = 531 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.961 ms/op
     p(99.9000) =      9.087 ms/op
     p(99.9900) =     14.891 ms/op
     p(99.9990) =     23.349 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 4.800 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.009 ms/op
Iteration   1: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  10.109 ms/op
                 listUser·p0.9999: 14.687 ms/op
                 listUser·p1.00:   16.466 ms/op

Iteration   2: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.775 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.505 ms/op
                 listUser·p0.999:  9.748 ms/op
                 listUser·p0.9999: 11.158 ms/op
                 listUser·p1.00:   11.420 ms/op

Iteration   3: 3.034 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  9.448 ms/op
                 listUser·p0.9999: 17.612 ms/op
                 listUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316647
  mean =      3.029 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 88948 
    [ 2.500,  3.750) = 187030 
    [ 3.750,  5.000) = 33095 
    [ 5.000,  6.250) = 5937 
    [ 6.250,  7.500) = 710 
    [ 7.500,  8.750) = 261 
    [ 8.750, 10.000) = 263 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.798 ms/op
     p(99.9900) =     15.046 ms/op
     p(99.9990) =     17.760 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


# Run complete. Total time: 00:13:01

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.343 ± 1.850  ops/ms
ClientPb.existUser                       thrpt       3  12.942 ± 0.959  ops/ms
ClientPb.getUser                         thrpt       3  12.757 ± 0.552  ops/ms
ClientPb.listUser                        thrpt       3  10.474 ± 1.699  ops/ms
ClientPb.createUser                       avgt       3   2.549 ± 0.727   ms/op
ClientPb.existUser                        avgt       3   2.499 ± 0.359   ms/op
ClientPb.getUser                          avgt       3   2.517 ± 0.454   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.048   ms/op
ClientPb.createUser                     sample  379456   2.527 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.855           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.99    sample           4.014           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.684           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.813           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.007           ms/op
ClientPb.existUser                      sample  387005   2.478 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.841           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.908           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.078           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.079           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.596           ms/op
ClientPb.getUser                        sample  381454   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.863           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.072           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.087           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.891           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.855           ms/op
ClientPb.listUser                       sample  316647   3.029 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.775           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.798           ms/op
ClientPb.listUser:listUser·p0.9999      sample          15.046           ms/op
ClientPb.listUser:listUser·p1.00        sample          17.793           ms/op
