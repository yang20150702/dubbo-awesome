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
# Warmup Iteration   1: 1.709 ops/ms
# Warmup Iteration   2: 3.770 ops/ms
# Warmup Iteration   3: 7.611 ops/ms
Iteration   1: 8.288 ops/ms
Iteration   2: 8.287 ops/ms
Iteration   3: 8.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.267 ±(99.9%) 0.647 ops/ms [Average]
  (min, avg, max) = (8.226, 8.267, 8.288), stdev = 0.035
  CI (99.9%): [7.620, 8.914] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.422 ops/ms
# Warmup Iteration   2: 6.752 ops/ms
# Warmup Iteration   3: 8.280 ops/ms
Iteration   1: 8.608 ops/ms
Iteration   2: 8.754 ops/ms
Iteration   3: 8.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.739 ±(99.9%) 2.255 ops/ms [Average]
  (min, avg, max) = (8.608, 8.739, 8.854), stdev = 0.124
  CI (99.9%): [6.484, 10.994] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.281 ops/ms
# Warmup Iteration   2: 6.965 ops/ms
# Warmup Iteration   3: 8.080 ops/ms
Iteration   1: 8.122 ops/ms
Iteration   2: 8.458 ops/ms
Iteration   3: 8.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.335 ±(99.9%) 3.379 ops/ms [Average]
  (min, avg, max) = (8.122, 8.335, 8.458), stdev = 0.185
  CI (99.9%): [4.956, 11.714] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.551 ops/ms
# Warmup Iteration   2: 5.141 ops/ms
# Warmup Iteration   3: 6.779 ops/ms
Iteration   1: 7.324 ops/ms
Iteration   2: 7.163 ops/ms
Iteration   3: 7.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.286 ±(99.9%) 2.001 ops/ms [Average]
  (min, avg, max) = (7.163, 7.286, 7.372), stdev = 0.110
  CI (99.9%): [5.286, 9.287] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 12.245 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.439 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.122 ±(99.9%) 0.010 ms/op
Iteration   1: 3.725 ±(99.9%) 0.015 ms/op
Iteration   2: 3.849 ±(99.9%) 0.005 ms/op
Iteration   3: 3.841 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.805 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (3.725, 3.805, 3.849), stdev = 0.069
  CI (99.9%): [2.540, 5.070] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.435 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.344 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.003 ms/op
Iteration   1: 3.686 ±(99.9%) 0.008 ms/op
Iteration   2: 3.719 ±(99.9%) 0.005 ms/op
Iteration   3: 3.827 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.744 ±(99.9%) 1.346 ms/op [Average]
  (min, avg, max) = (3.686, 3.744, 3.827), stdev = 0.074
  CI (99.9%): [2.398, 5.090] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.498 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.014 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.009 ms/op
Iteration   1: 3.770 ±(99.9%) 0.011 ms/op
Iteration   2: 3.796 ±(99.9%) 0.009 ms/op
Iteration   3: 3.785 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.784 ±(99.9%) 0.230 ms/op [Average]
  (min, avg, max) = (3.770, 3.784, 3.796), stdev = 0.013
  CI (99.9%): [3.553, 4.014] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 12.493 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.104 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.679 ±(99.9%) 0.007 ms/op
Iteration   1: 4.459 ±(99.9%) 0.013 ms/op
Iteration   2: 4.518 ±(99.9%) 0.012 ms/op
Iteration   3: 4.501 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.493 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (4.459, 4.493, 4.518), stdev = 0.031
  CI (99.9%): [3.934, 5.052] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.967 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.288 ±(99.9%) 0.017 ms/op
Iteration   1: 3.823 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.835 ms/op
                 createUser·p0.50:   3.666 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.734 ms/op
                 createUser·p0.999:  11.199 ms/op
                 createUser·p0.9999: 27.903 ms/op
                 createUser·p1.00:   28.836 ms/op

Iteration   2: 4.059 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.272 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.792 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   7.577 ms/op
                 createUser·p0.999:  26.489 ms/op
                 createUser·p0.9999: 31.199 ms/op
                 createUser·p1.00:   31.457 ms/op

Iteration   3: 3.896 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.718 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  25.583 ms/op
                 createUser·p0.9999: 39.715 ms/op
                 createUser·p1.00:   40.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244568
  mean =      3.924 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 231704 
    [ 5.000, 10.000) = 12268 
    [10.000, 15.000) = 324 
    [15.000, 20.000) = 16 
    [20.000, 25.000) = 26 
    [25.000, 30.000) = 144 
    [30.000, 35.000) = 48 
    [35.000, 40.000) = 36 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     24.225 ms/op
     p(99.9900) =     36.801 ms/op
     p(99.9990) =     39.984 ms/op
     p(99.9999) =     40.108 ms/op
    p(100.0000) =     40.108 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.592 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.012 ms/op
Iteration   1: 3.960 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.808 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   5.153 ms/op
                 existUser·p0.99:   6.636 ms/op
                 existUser·p0.999:  14.390 ms/op
                 existUser·p0.9999: 25.166 ms/op
                 existUser·p1.00:   26.247 ms/op

Iteration   2: 3.690 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.792 ms/op
                 existUser·p0.50:   3.596 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.661 ms/op
                 existUser·p0.99:   6.275 ms/op
                 existUser·p0.999:  11.962 ms/op
                 existUser·p0.9999: 28.596 ms/op
                 existUser·p1.00:   29.753 ms/op

Iteration   3: 3.692 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.153 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   5.939 ms/op
                 existUser·p0.999:  28.553 ms/op
                 existUser·p0.9999: 32.309 ms/op
                 existUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 253988
  mean =      3.776 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1052 
    [ 2.500,  5.000) = 242397 
    [ 5.000,  7.500) = 9274 
    [ 7.500, 10.000) = 637 
    [10.000, 12.500) = 255 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     31.313 ms/op
     p(99.9990) =     32.702 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.141 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.610 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.013 ms/op
Iteration   1: 3.949 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.530 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   7.709 ms/op
                 getUser·p0.999:  21.889 ms/op
                 getUser·p0.9999: 27.915 ms/op
                 getUser·p1.00:   27.951 ms/op

Iteration   2: 3.920 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.063 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  10.655 ms/op
                 getUser·p0.9999: 28.377 ms/op
                 getUser·p1.00:   29.950 ms/op

Iteration   3: 3.859 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.688 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   4.981 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  28.705 ms/op
                 getUser·p0.9999: 38.057 ms/op
                 getUser·p1.00:   38.601 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245669
  mean =      3.909 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 899 
    [ 2.500,  5.000) = 231602 
    [ 5.000,  7.500) = 11236 
    [ 7.500, 10.000) = 1350 
    [10.000, 12.500) = 266 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 104 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.063 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     21.802 ms/op
     p(99.9900) =     36.663 ms/op
     p(99.9990) =     38.470 ms/op
     p(99.9999) =     38.601 ms/op
    p(100.0000) =     38.601 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.628 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 5.087 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.606 ±(99.9%) 0.015 ms/op
Iteration   1: 4.650 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   6.234 ms/op
                 listUser·p0.99:   9.224 ms/op
                 listUser·p0.999:  24.940 ms/op
                 listUser·p0.9999: 26.917 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 4.629 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.556 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  17.990 ms/op
                 listUser·p0.9999: 21.692 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   3: 4.477 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  16.584 ms/op
                 listUser·p0.9999: 19.759 ms/op
                 listUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209377
  mean =      4.584 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 182008 
    [ 5.000,  7.500) = 22709 
    [ 7.500, 10.000) = 3463 
    [10.000, 12.500) = 432 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 295 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 65 

  Percentiles, ms/op:
      p(0.0000) =      1.663 ms/op
     p(50.0000) =      4.391 ms/op
     p(90.0000) =      5.153 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      8.585 ms/op
     p(99.9000) =     19.759 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.267 ± 0.647  ops/ms
ClientPb.existUser                       thrpt       3   8.739 ± 2.255  ops/ms
ClientPb.getUser                         thrpt       3   8.335 ± 3.379  ops/ms
ClientPb.listUser                        thrpt       3   7.286 ± 2.001  ops/ms
ClientPb.createUser                       avgt       3   3.805 ± 1.265   ms/op
ClientPb.existUser                        avgt       3   3.744 ± 1.346   ms/op
ClientPb.getUser                          avgt       3   3.784 ± 0.230   ms/op
ClientPb.listUser                         avgt       3   4.493 ± 0.559   ms/op
ClientPb.createUser                     sample  244568   3.924 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.272           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.723           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.620           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.038           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.889           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.225           ms/op
ClientPb.createUser:createUser·p0.9999  sample          36.801           ms/op
ClientPb.createUser:createUser·p1.00    sample          40.108           ms/op
ClientPb.existUser                      sample  253988   3.776 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.430           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.882           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.496           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.254           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.313           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.965           ms/op
ClientPb.getUser                        sample  245669   3.909 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.063           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.768           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.063           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.225           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.802           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.663           ms/op
ClientPb.getUser:getUser·p1.00          sample          38.601           ms/op
ClientPb.listUser                       sample  209377   4.584 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.663           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.153           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.751           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.585           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.759           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.509           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394           ms/op
