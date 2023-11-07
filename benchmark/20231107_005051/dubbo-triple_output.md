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
# Warmup Iteration   1: 1.530 ops/ms
# Warmup Iteration   2: 3.337 ops/ms
# Warmup Iteration   3: 7.016 ops/ms
Iteration   1: 7.373 ops/ms
Iteration   2: 7.856 ops/ms
Iteration   3: 7.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.726 ±(99.9%) 5.641 ops/ms [Average]
  (min, avg, max) = (7.373, 7.726, 7.948), stdev = 0.309
  CI (99.9%): [2.085, 13.366] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.359 ops/ms
# Warmup Iteration   2: 6.845 ops/ms
# Warmup Iteration   3: 7.871 ops/ms
Iteration   1: 8.083 ops/ms
Iteration   2: 8.373 ops/ms
Iteration   3: 8.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.229 ±(99.9%) 2.640 ops/ms [Average]
  (min, avg, max) = (8.083, 8.229, 8.373), stdev = 0.145
  CI (99.9%): [5.589, 10.869] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.183 ops/ms
# Warmup Iteration   2: 6.430 ops/ms
# Warmup Iteration   3: 7.500 ops/ms
Iteration   1: 7.746 ops/ms
Iteration   2: 7.624 ops/ms
Iteration   3: 8.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.806 ±(99.9%) 3.997 ops/ms [Average]
  (min, avg, max) = (7.624, 7.806, 8.049), stdev = 0.219
  CI (99.9%): [3.809, 11.804] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.240 ops/ms
# Warmup Iteration   2: 6.012 ops/ms
# Warmup Iteration   3: 6.552 ops/ms
Iteration   1: 6.432 ops/ms
Iteration   2: 6.815 ops/ms
Iteration   3: 6.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.657 ±(99.9%) 3.656 ops/ms [Average]
  (min, avg, max) = (6.432, 6.657, 6.815), stdev = 0.200
  CI (99.9%): [3.001, 10.314] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 12.258 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.596 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.196 ±(99.9%) 0.002 ms/op
Iteration   1: 4.150 ±(99.9%) 0.004 ms/op
Iteration   2: 4.122 ±(99.9%) 0.004 ms/op
Iteration   3: 3.925 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.066 ±(99.9%) 2.238 ms/op [Average]
  (min, avg, max) = (3.925, 4.066, 4.150), stdev = 0.123
  CI (99.9%): [1.827, 6.304] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.383 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.003 ms/op
Iteration   1: 3.790 ±(99.9%) 0.005 ms/op
Iteration   2: 3.854 ±(99.9%) 0.006 ms/op
Iteration   3: 3.810 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.818 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (3.790, 3.818, 3.854), stdev = 0.033
  CI (99.9%): [3.216, 4.420] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 12.870 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.338 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.004 ms/op
Iteration   1: 4.079 ±(99.9%) 0.004 ms/op
Iteration   2: 4.018 ±(99.9%) 0.004 ms/op
Iteration   3: 3.949 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.015 ±(99.9%) 1.185 ms/op [Average]
  (min, avg, max) = (3.949, 4.015, 4.079), stdev = 0.065
  CI (99.9%): [2.831, 5.200] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.108 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.333 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.942 ±(99.9%) 0.006 ms/op
Iteration   1: 4.838 ±(99.9%) 0.009 ms/op
Iteration   2: 4.806 ±(99.9%) 0.007 ms/op
Iteration   3: 4.820 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.821 ±(99.9%) 0.289 ms/op [Average]
  (min, avg, max) = (4.806, 4.821, 4.838), stdev = 0.016
  CI (99.9%): [4.532, 5.111] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.539 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.455 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.479 ±(99.9%) 0.018 ms/op
Iteration   1: 4.048 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.651 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.547 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   8.536 ms/op
                 createUser·p0.999:  21.955 ms/op
                 createUser·p0.9999: 23.993 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   2: 4.059 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.761 ms/op
                 createUser·p0.50:   3.932 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.627 ms/op
                 createUser·p0.999:  25.475 ms/op
                 createUser·p0.9999: 29.098 ms/op
                 createUser·p1.00:   30.441 ms/op

Iteration   3: 4.032 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   7.465 ms/op
                 createUser·p0.999:  16.774 ms/op
                 createUser·p0.9999: 28.774 ms/op
                 createUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 237259
  mean =      4.046 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 282 
    [ 2.500,  5.000) = 225909 
    [ 5.000,  7.500) = 8565 
    [ 7.500, 10.000) = 1630 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 301 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.998 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      7.594 ms/op
     p(99.9000) =     22.012 ms/op
     p(99.9900) =     28.592 ms/op
     p(99.9990) =     30.016 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.147 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.013 ms/op
Iteration   1: 3.905 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.841 ms/op
                 existUser·p0.99:   6.849 ms/op
                 existUser·p0.999:  22.549 ms/op
                 existUser·p0.9999: 25.023 ms/op
                 existUser·p1.00:   25.887 ms/op

Iteration   2: 3.914 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.163 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   4.809 ms/op
                 existUser·p0.99:   6.965 ms/op
                 existUser·p0.999:  15.023 ms/op
                 existUser·p0.9999: 26.842 ms/op
                 existUser·p1.00:   27.230 ms/op

Iteration   3: 3.836 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.942 ms/op
                 existUser·p0.50:   3.682 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.636 ms/op
                 existUser·p0.999:  14.729 ms/op
                 existUser·p0.9999: 28.115 ms/op
                 existUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246922
  mean =      3.885 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 229 
    [ 2.500,  5.000) = 237477 
    [ 5.000,  7.500) = 7528 
    [ 7.500, 10.000) = 995 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     15.335 ms/op
     p(99.9900) =     27.197 ms/op
     p(99.9990) =     29.517 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.330 ±(99.9%) 0.175 ms/op
# Warmup Iteration   2: 4.837 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.155 ±(99.9%) 0.012 ms/op
Iteration   1: 4.209 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.036 ms/op
                 getUser·p0.50:   4.014 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   8.749 ms/op
                 getUser·p0.999:  24.473 ms/op
                 getUser·p0.9999: 27.583 ms/op
                 getUser·p1.00:   29.196 ms/op

Iteration   2: 4.009 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.298 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  9.699 ms/op
                 getUser·p0.9999: 27.233 ms/op
                 getUser·p1.00:   28.475 ms/op

Iteration   3: 4.148 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.841 ms/op
                 getUser·p0.50:   4.035 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  26.832 ms/op
                 getUser·p0.9999: 29.566 ms/op
                 getUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232897
  mean =      4.120 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 222649 
    [ 5.000,  7.500) = 7824 
    [ 7.500, 10.000) = 1642 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 159 
    [27.500, 30.000) = 58 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.841 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      7.561 ms/op
     p(99.9000) =     24.481 ms/op
     p(99.9900) =     28.466 ms/op
     p(99.9990) =     29.820 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.139 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 5.319 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.898 ±(99.9%) 0.016 ms/op
Iteration   1: 4.804 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.826 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   8.274 ms/op
                 listUser·p0.999:  23.757 ms/op
                 listUser·p0.9999: 27.472 ms/op
                 listUser·p1.00:   29.098 ms/op

Iteration   2: 4.929 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.870 ms/op
                 listUser·p0.50:   4.817 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  16.914 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   3: 4.849 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.396 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   5.300 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   7.979 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 21.818 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 197284
  mean =      4.860 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 144045 
    [ 5.000,  7.500) = 49357 
    [ 7.500, 10.000) = 2978 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 197 
    [15.000, 17.500) = 203 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.870 ms/op
     p(50.0000) =      4.743 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      8.233 ms/op
     p(99.9000) =     18.692 ms/op
     p(99.9900) =     26.977 ms/op
     p(99.9990) =     27.887 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.726 ± 5.641  ops/ms
ClientPb.existUser                       thrpt       3   8.229 ± 2.640  ops/ms
ClientPb.getUser                         thrpt       3   7.806 ± 3.997  ops/ms
ClientPb.listUser                        thrpt       3   6.657 ± 3.656  ops/ms
ClientPb.createUser                       avgt       3   4.066 ± 2.238   ms/op
ClientPb.existUser                        avgt       3   3.818 ± 0.602   ms/op
ClientPb.getUser                          avgt       3   4.015 ± 1.185   ms/op
ClientPb.listUser                         avgt       3   4.821 ± 0.289   ms/op
ClientPb.createUser                     sample  237259   4.046 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.998           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.579           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.964           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.594           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.012           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.592           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.441           ms/op
ClientPb.existUser                      sample  246922   3.885 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.163           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.350           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.768           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.791           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.335           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.197           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.030           ms/op
ClientPb.getUser                        sample  232897   4.120 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.841           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.907           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.561           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.481           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.466           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.540           ms/op
ClientPb.listUser                       sample  197284   4.860 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.870           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.333           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.233           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.692           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.977           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.098           ms/op
